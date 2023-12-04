# FastAPI 101

## Run

```sh
# run in dev mode
uvicorn storeapi.main:app --reload
# run
uvicorn storeapi.main:app
```

## Setup environment

```sh
# Create a .python-version file
pyenv local 3.11.6
# Create a virtual environment
pyenv exec python -m venv .venv
```