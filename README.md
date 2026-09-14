# is218-python-workflow

Practice project for IS218 demonstrating a GitHub issue → commit → test workflow with a simple Python function.

## Environment Setup

Python version: 3.12.14

Setup commands:
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt

To reactivate later, from the project root:
source .venv/bin/activate

## Files

- `README.md` — this file
- `.gitignore` — excludes .venv, __pycache__, .pytest_cache, and compiled Python files
- `requirements.txt` — pins pytest==8.4.2
- `app.py` — contains the `add` function
- `tests/test_app.py` — contains 2 tests: test_add and test_add_negative

## Repository

https://github.com/GaretJax6905/is218-python-workflow

## Tests

2 tests passing (verified with Python 3.12.14, pytest 8.4.2)