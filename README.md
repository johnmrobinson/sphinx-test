This archive has an associated virtualenv.

## Environment Setup

http://docs.python-guide.org/en/latest/dev/virtualenvs/

Before working on this project execute

```
workon sphinx-test
```

Before committing, save off the project requirements using

```
pip freeze > requirements.txt
```

## Build

```
make html
```

## Theme

```
pip install sphinx_rtd_theme
```

In `conf.py`,

```
html_theme = "sphinx_rtd_theme"
```
