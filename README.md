# template-python-script

[![Ruff](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/astral-sh/ruff/main/assets/badge/v2.json)](https://github.com/astral-sh/ruff)

Opinionated [Python](https://www.python.org/) template for new scripts.

## Getting Started

1. Go to or create the project folder.
2. Get the template files:

```bash
npx degit github:joaopalmeiro/template-python-script
```

or

```bash
npx degit github:joaopalmeiro/template-python-script --force
```

3. Search for `template-python-script` and replace it with the project name.
4. Search for `Opinionated [Python](https://www.python.org/) template for new scripts.` and replace it with the (short) project description.
5. Search for `João Palmeiro` and replace it with the author's name.
6. Install [pyenv](https://github.com/pyenv/pyenv) (if necessary).
7. Run the first two commands in the [`Development` section](#development) to install Python and [Pipenv](https://github.com/pypa/pipenv) (if necessary).
8. Run the third command in the [`Development` section](#development) to create the virtual environment.
9. Open the [NOTES.md](NOTES.md) file and install the project-specific dependencies according to the first command in the [Commands section](NOTES.md#commands).
10. Delete the [`Template References` section](NOTES.md#template-references) from the [NOTES.md](NOTES.md) file.
11. Delete the [`Getting Started` section](#getting-started).

## Development

Install [pyenv](https://github.com/pyenv/pyenv) (if necessary).

```bash
pyenv install && pyenv versions
```

```bash
pip install pipenv==2023.11.15 && pipenv --version
```

```bash
pipenv install --dev --skip-lock
```

```bash
pipenv run codespell
```

```bash
pipenv run ruff check .
```

```bash
pipenv run ruff check --fix .
```

```bash
pipenv run ruff format .
```

```bash
pipenv run python 01.py
```
