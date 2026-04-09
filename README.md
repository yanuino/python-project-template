# Python Project Template

## Development setup

This project uses **uv** for dependency management and **pre-commit** for code quality.

### Prerequisites

* Git
* Python **3.11+**
* [uv](https://github.com/astral-sh/uv)

### Setup (Linux / macOS / WSL)

```bash
./scripts/dev-setup.sh
```

### Setup (Windows - Powershell)

```pwsh
.\\scripts\\dev-setup.ps1
```

#### If script execution is restricted on your system:

```pwsh
PowerShell -ExecutionPolicy Bypass -File scripts\\dev-setup.ps1
```

## Tooling upgrades

Ruff and pre-commit versions are intentionally pinned.

Upgrades are performed manually and always include:
- running Ruff with auto-fix and format
- updating pre-commit hooks
- committing all formatting changes

This ensures reproducible behavior across environments.
