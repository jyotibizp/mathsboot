# Setup Guide

## Prerequisites

- Python 3.11+
- Git
- Optional: Docker Desktop / Docker Engine

## Create a virtual environment

Linux/macOS:

```bash
python3 -m venv venv
source venv/bin/activate
pip install -r root_files/requirements.txt
```

Windows (PowerShell):

```powershell
python -m venv venv
.\venv\Scripts\Activate.ps1
pip install -r root_files/requirements.txt
```

Verify:

```bash
python --version
pip list | grep -E "numpy|scipy|pandas|matplotlib|sympy" || true
```

## Jupyter Lab

Local install:

```bash
jupyter lab
```

Docker (optional):

```bash
docker compose -f root_files/docker-compose.yml up -d
# Then open http://localhost:8888
```

## Recommended editor

- VS Code with extensions: Python, Jupyter (optional), Markdown All in One

## Next steps

1. Read `welcome.md`
2. Start with `1-mathematics/linear-algebra/lessons/`
3. Attempt exercises before viewing solutions
