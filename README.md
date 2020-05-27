# pytorch-tutorial

1. Pyenv + Poetry で環境構築

- Install pyenv
```
brew install pyenv
```

- Install Poetry
```
# Refer : Poetry Official Repository : https://github.com/python-poetry/poetry#installation
$ curl -sSL https://raw.githubusercontent.com/python-poetry/poetry/master/get-poetry.py | python
source ~/.bash_profile


# Check if it's installed.
$ poetry self update
You are using the latest version

# Setting to create a .venv in the project directory.
poetry config virtualenvs.in-project true

# Reference : https://qiita.com/yano404/items/85f21897e417f03236c9
```
