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


```bash
usage: vid h2r [-h] [-o OUTPUT] [-i] [-sv] [-s] [-c] [-a] [-l] [-w]
               [-t START_TIME]
               input

Tools for hum hai rahi channel

positional arguments:
  input                 Input video to add the file.

optional arguments:
  -h, --help            show this help message and exit
  -o OUTPUT, --output OUTPUT
                        Output file name
  -i, --intro           Adds Hum Hai Rahi intro video greenscreen
  -sv, --subscribe-voice
                        Adds subscribe greenscreen with voice
  -s, --subscribe       Adds subscribe greenscreen with no voice
  -c, --consider        Adds consider subscribing voice over
  -a, --apna-desh       Adds apna desh voice over
  -l, --like            Adds like-comment voice over
  -w, --watching        Adds you are watching voice over
  -t START_TIME, --start-time START_TIME
                        Start time if given default=1

```

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
