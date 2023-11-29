# template-python-script

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
6. Run the first two commands in the [`Development` section](#development) to install [pyenv](https://github.com/pyenv/pyenv) and [Pipenv](https://github.com/pypa/pipenv) (if necessary).
7. Run the third command in the [`Development` section](#development) to create the virtual environment.
8. Open the [NOTES.md](NOTES.md) file and install the dependencies according to the [`Example command to install dependencies and development dependencies`](NOTES.md#example-command-to-install-dependencies-and-development-dependencies). Use the first command in the [Commands section](NOTES.md#commands) as a template.
9. Delete the [`Template References` section](NOTES.md#template-references) from the [NOTES.md](NOTES.md) file.
10. Delete the [`Getting Started` section](#getting-started).

## Development

```bash
pyenv install && pyenv versions
```

```bash
pip install pipenv && pipenv --version
```

```bash
pipenv install --dev --skip-lock
```

```bash
pipenv run ruff check --verbose .
```

```bash
pipenv run ruff check --fix --verbose . && pipenv run ruff format --verbose .
```

```bash
pipenv run python 01.py
```
