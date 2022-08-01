# Space Telescope Environment Distribution

[![build](https://github.com/spacetelescope/spacetelescope-env-distribution/actions/workflows/build.yml/badge.svg)](https://github.com/spacetelescope/spacetelescope-env-distribution/actions/workflows/build.yml)
[![release](https://img.shields.io/github/v/release/spacetelescope/spacetelescope-env-distribution)](https://github.com/spacetelescope/spacetelescope-env-distribution/releases)

> :warning: **This distribution platform is still in testing and is not yet an official release.**

This repository builds YAML files that define frozen environments (sets of packages at specific versions) for an
Anaconda installation. The [Releases page](https://github.com/spacetelescope/spacetelescope-env-distribution/releases)
provides a YAML file for each release.

## Installation

1. install Anaconda - https://docs.conda.io/en/latest/miniconda.html
2. pick a release from the [Releases page](https://github.com/spacetelescope/spacetelescope-env-distribution/releases)
   and download the accompanying YAML file
3. create a new Anaconda environment from the YAML file
   ```shell
   conda env create --file spacetelescope-env-macOS-py3.9-20220808.yml -n spacetelescope-env-macOS-py3.9-v0.3.0
   ```
4. activate the environment
   ```shell
   conda activate spacetelescope-env-macOS-py3.9-20220808
   ```