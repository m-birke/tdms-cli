# tdms-cli

|     |     |
| --- | --- |
| Version | [![PyPI - Version](https://img.shields.io/pypi/v/tdms-cli.svg)](https://pypi.org/project/tdms-cli) [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/tdms-cli.svg)](https://pypi.org/project/tdms-cli) |
| Project | ![GitHub License](https://img.shields.io/github/license/m-birke/tdms-cli) ![PyPI - Status](https://img.shields.io/pypi/status/tdms-cli) ![PyPI - Format](https://img.shields.io/pypi/format/tdms-cli) ![PyPI - Implementation](https://img.shields.io/pypi/implementation/tdms-cli) |
| CI | ![GitHub Actions Workflow Status](https://img.shields.io/github/actions/workflow/status/m-birke/tdms-cli/static-code-check.yml) |
| Code | ![PyPI - Types](https://img.shields.io/pypi/types/tdms-cli) [![Checked with mypy](https://www.mypy-lang.org/static/mypy_badge.svg)](https://mypy-lang.org/) [![Linting: Ruff](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/charliermarsh/ruff/main/assets/badge/v2.json)](https://github.com/astral-sh/ruff) [![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black) |

-----

Small util to analyze TDMS files quickly via CLI

## Table of Contents

- [About](#about)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)

## About

`tdms-cli` is a small tool to analyze [TDMS files](https://www.ni.com/en/support/documentation/supplemental/06/the-ni-tdms-file-format.html) easily via CLI. It depends on [npTDMS](https://nptdms.readthedocs.io/en/stable/index.html).

## Installation

```console
pip install tdms-cli
```

## Usage

```sh
$ tu --help
```

## License

`tdms-cli` is distributed under the terms of the [MIT](https://spdx.org/licenses/MIT.html) license.
