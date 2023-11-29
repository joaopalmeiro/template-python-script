# Notes

## Template References

- https://docs.astral.sh/ruff/settings/#cache-dir (`.ruff_cache` by default)
- https://github.com/astral-sh/ruff/releases/tag/v0.1.6

### Example command to install dependencies and development dependencies

- `pipenv install --skip-lock tinycss2==1.2.1 w3lib==2.1.2 && pipenv install --dev --skip-lock ruff==0.1.6`

## Commands

```bash
pipenv install --skip-lock ... && pipenv install --dev --skip-lock ruff==0.1.6
```
