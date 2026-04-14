# Tailspend

## Cursor Cloud specific instructions

- **Python project (skeleton stage):** The repo currently has no application code, dependencies, or services. The development environment is a Python 3.12 virtualenv at `/workspace/.venv`.
- **Activate the venv** before running any Python/pip commands: `source /workspace/.venv/bin/activate`
- **The original README references macOS-specific paths** (`/Users/countryinterests/Documents/Github/venv`). These do not exist in the Cloud VM. Use `/workspace/.venv` instead.
- **No lint, test, or build commands exist yet.** As the project grows and gains a `requirements.txt`, `pyproject.toml`, or similar, the update script and these instructions should be updated accordingly.
- **`python3.12-venv` must be installed** (via `apt`) before creating the venv. The update script handles venv creation if it doesn't already exist.
