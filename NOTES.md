# Notes

## Template References

- Ruff:
  - https://docs.astral.sh/ruff/settings/#cache-dir (`.ruff_cache` by default)
  - https://github.com/astral-sh/ruff/releases/tag/v0.1.6
  - https://github.com/astral-sh/ruff/releases/tag/v0.1.11
  - https://astral.sh/blog/ruff-v0.2.0
  - https://github.com/astral-sh/ruff/releases/tag/v0.2.0
  - https://docs.astral.sh/ruff/configuration/
  - https://docs.astral.sh/ruff/linter/#ruff-check: `ruff check .`
  - https://docs.astral.sh/ruff/formatter/#ruff-format: `ruff format .`
- Pipenv:
  - https://github.com/pypa/pipenv/releases
  - https://peps.python.org/pep-0619/ (`3.10.13`)
  - https://github.com/pypa/pipenv/releases
  - https://pypi.org/project/pipenv/

### Example command to install dependencies and development dependencies

- `pipenv install --skip-lock tinycss2==1.2.1 w3lib==2.1.2 && pipenv install --dev --skip-lock ruff==0.1.11`

### Snippets

```markdown
8. Open the [NOTES.md](NOTES.md) file and install the dependencies according to the [`Example command to install dependencies and development dependencies`](NOTES.md#example-command-to-install-dependencies-and-development-dependencies). Use the first command in the [`Commands` section](NOTES.md#commands) as a template.
```

## Commands

```bash
pipenv install --skip-lock ... && pipenv install --dev --skip-lock ruff==0.2.1 codespell==2.2.6
```

```bash
pipenv --rm
```

```bash
pipenv run codespell --help
```

```bash
pipenv run ruff check --help
```

```bash
pipenv run ruff format --help
```
