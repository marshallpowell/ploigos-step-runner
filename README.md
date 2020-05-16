![Publish Dev](https://github.com/rhtconsulting/tssc-python-package/workflows/Publish%20Dev/badge.svg?branch=master)
![Publish GitHub Pages](https://github.com/rhtconsulting/tssc-python-package/workflows/Publish%20GitHub%20Pages/badge.svg?branch=master)
[![Code Coverage](https://codecov.io/gh/rhtconsulting/tssc-python-package/branch/master/graph/badge.svg)](https://codecov.io/gh/rhtconsulting/tssc-python-package)

# tssc-python-package
Trusted Software Supply Chain (TSSC) implemented as a Python library.

## Documenation

- [Python Package Documenation](https://rhtconsulting.github.io/tssc-python-package/)
- [TSSC](https://rhtconsulting.github.io/tssc-docs/)

## Install

Latest Release
```bash
not yet released
```

Latest Development Release
```bash
pip install --index-url https://test.pypi.org/simple/ --extra-index-url https://pypi.org/simple tssc
```

## Development

### Set Up Development Environment
```bash
cd tssc-python-package
python -m venv .venvs/set-dev
source .venvs/set-dev/bin/activate
pip install --upgrade pip
pip install -e .[tests]
```

### Run Tests
```bash
pytest --cov=tssc tests/
```