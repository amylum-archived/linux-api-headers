linux-api-headers
==========

[![Build Status](https://img.shields.io/circleci/project/amylum/linux-api-headers.svg)](https://circleci.com/gh/amylum/linux-api-headers)
[![GitHub release](https://img.shields.io/github/release/amylum/linux-api-headers.svg)](https://github.com/amylum/linux-api-headers/releases)
[![GPL2 Licensed](http://img.shields.io/badge/license-GPL2-green.svg)](https://tldrlegal.com/license/gnu-general-public-license-v2)

Package repo for [linux-api-headers](https://kernel.org). This packages specifically the headers for compiling userspace codebases.

## Usage

To build a new package, update the submodule and run `make`. This launches the docker build container and builds the package.

To start a shell in the build environment for manual actions, run `make manual`.

## License

This repo is released under the MIT License. See the bundled LICENSE file for details.

