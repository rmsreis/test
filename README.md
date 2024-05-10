# Poetry: Dependency Management for Python

Poetry helps you declare, manage, and install dependencies of Python projects,
ensuring you have the right stack everywhere.

![Poetry Install](https://raw.githubusercontent.com/python-poetry/poetry/master/assets/install.gif)

It supports Python 2.7 and 3.5+.

> **Note** Python 2.7 and 3.5 will no longer be supported in the next feature release (1.2). You should consider updating your Python version to a supported one.

[![Tests status](https://github.com/python-poetry/poetry/workflows/Tests/badge.svg?branch=master&event=push)](https://github.com/python-poetry/poetry/actions?query=workflow%3ATests+branch%3Amaster+event%3Apush)

The [complete documentation](https://python-poetry.org/docs/) is available on the [official website](https://python-poetry.org).

## Installation

Poetry provides a custom installer that will install `poetry` isolated
from the rest of your system.

### osx / linux / bash for Windows install instructions

```bash
curl -sSL https://raw.githubusercontent.com/python-poetry/poetry/master/install-poetry.py | python -
```

### Windows powershell install instructions

```powershell
(Invoke-WebRequest -Uri https://raw.githubusercontent.com/python-poetry/poetry/master/install-poetry.py -UseBasicParsing).Content | python -
```