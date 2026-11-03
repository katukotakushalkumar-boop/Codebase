# myproject

A simple Python project.

## Setup

```powershell
python -m venv .venv
.venv\Scripts\Activate.ps1
pip install -e ".[dev]"
```

## Run

```powershell
python -m myproject.main Alice
# or, after install:
myproject Alice
```

## Test

```powershell
pytest
```
