# Contributing to Rapid Materials Aging Chamber

Thank you for your interest in contributing to the OCN ecosystem!

## Code of Conduct

All contributors are expected to uphold the [GALACTIC-UNION Code of Conduct](https://github.com/GALACTIC-UNION/.github/blob/main/CODE_OF_CONDUCT.md).

## How to Contribute

### 1. Fork and Clone

```bash
git clone https://github.com/<your-username>/rapid-materials-aging-chamber.git
cd rapid-materials-aging-chamber
git remote add upstream https://github.com/GALACTIC-UNION/rapid-materials-aging-chamber.git
```

### 2. Create a Branch

Use the naming convention: `feat/`, `fix/`, `docs/`, `test/`, or `chore/`.

```bash
git checkout -b feat/my-feature
```

### 3. Set Up the Development Environment

```bash
pip install -r config/requirements.txt
pip install pytest pytest-cov flake8 mypy black isort
pre-commit install
```

### 4. Make Your Changes

- Write code in `src/` following the existing module structure.
- Add or update tests in `tests/` — aim for ≥ 90 % coverage on new code.
- Follow [PEP 8](https://peps.python.org/pep-0008/) for Python code style.

### 5. Run Tests Locally

```bash
pytest tests/ -v --cov=src --cov-report=term-missing
flake8 src/ tests/
mypy src/
```

### 6. Open a Pull Request

- Push to your fork and open a PR against `main`.
- CI must pass before merging.

## Reporting Issues

Use [GitHub Issues](https://github.com/GALACTIC-UNION/rapid-materials-aging-chamber/issues).

## Security Vulnerabilities

Email **security@galactic-union.io** — do not open a public issue.

## License

By contributing, you agree that your contributions will be licensed under the project's MIT License.
