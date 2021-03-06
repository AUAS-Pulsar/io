# Pulsar IO
[![Build Status](https://travis-ci.com/AUAS-Pulsar/io.svg?branch=master)](https://travis-ci.com/AUAS-Pulsar/io)
[![codecov](https://codecov.io/gh/AUAS-Pulsar/io/branch/master/graph/badge.svg)](https://codecov.io/gh/AUAS-Pulsar/io)


## Introduction

Creating a free and open source framework that contains the generic algorithms and file handling for astronomical data sets. This framework will be modular. Similar to OpenCV, wherein specific modules can be added and disabled depended on the needs of a project. This framework will be implemented in Python and C++.

## Installation

### Requirements

    * numpy
    * python 3.6


## Documentation

1. [Development](docs/Development.md)
    1. [Plan of Action](docs/Development.md#1-plan-of-action)
        1. [Introduction](docs/Development.md#11-introduction)
        2. [Current situation](docs/Development.md#12-current-situation)
        3. [Mission](docs/Development.md#13-mission)
        4. [Monitoring performance](docs/Development.md#14-monitoring-performance)
        5. [Risks](docs/Development.md#15-risks)
2. [Technical Details](docs/Technical.md)
    1. [Requirements](docs/Technical.md#2-requirements)
        1. [Functional](docs/Technical.md#21-functional)
        2. [Non-Functional](docs/Technical.md#22-non-functional)


## How to use the filterbank reader

### Read header data

1. Specify the path to the filterbank file in the header.py file (line 124)
2. Run the following command: `python header.py`