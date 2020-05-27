# pytorch-tutorial

## 1. Pytorch Environment Building with Pyenv + Poetry

- Install pyenv
```
brew install pyenv
```
- Install Poetry
```
# Refer : Poetry Official Repository : https://github.com/python-poetry/poetry#installation
curl -sSL https://raw.githubusercontent.com/python-poetry/poetry/master/get-poetry.py | python
source ~/.bash_profile


# Check if it's installed.
poetry self update
# >> You are using the latest version

# Setting to create a .venv in the project directory.
poetry config virtualenvs.in-project true

# Reference : https://qiita.com/yano404/items/85f21897e417f03236c9
```

- Make an environment for the project
```
# Make a directory
mkdir ./pytorch-tutorial
cd ./pytorch-tutorial

# Install Python 3.8.0 (PyTorch 1.4.0 supports Python 3, specifically 3.5, 3.6, 3.7 and 3.8)
pyenv install 3.8
# Define 3.8.0 as a project-specific version of Python
pyenv local 3.8.0

# Make a virtual environment and install necessary packages
poetry init
poetry install
```



