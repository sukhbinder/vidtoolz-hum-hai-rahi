# vidtoolz-hum-hai-rahi

[![PyPI](https://img.shields.io/pypi/v/vidtoolz-hum-hai-rahi.svg)](https://pypi.org/project/vidtoolz-hum-hai-rahi/)
[![Changelog](https://img.shields.io/github/v/release/sukhbinder/vidtoolz-hum-hai-rahi?include_prereleases&label=changelog)](https://github.com/sukhbinder/vidtoolz-hum-hai-rahi/releases)
[![Tests](https://github.com/sukhbinder/vidtoolz-hum-hai-rahi/workflows/Test/badge.svg)](https://github.com/sukhbinder/vidtoolz-hum-hai-rahi/actions?query=workflow%3ATest)
[![License](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](https://github.com/sukhbinder/vidtoolz-hum-hai-rahi/blob/main/LICENSE)

Tools for hum hai rahi channel

## Installation

First install [vidtoolz](https://github.com/sukhbinder/vidtoolz).

```bash
pip install vidtoolz
```

Then install this plugin in the same environment as your vidtoolz application.

```bash
vidtoolz install vidtoolz-hum-hai-rahi
```
## Usage

type ``vid h2r --help`` to get help



## Development

To set up this plugin locally, first checkout the code. Then create a new virtual environment:
```bash
cd vidtoolz-hum-hai-rahi
python -m venv venv
source venv/bin/activate
```
Now install the dependencies and test dependencies:
```bash
pip install -e '.[test]'
```
To run the tests:
```bash
python -m pytest
```
