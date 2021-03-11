# Change Log
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/)
and this project adheres to [Semantic Versioning](http://semver.org/).

## [Unreleased]


## [0.5 - 2019-05-10]
### Changed
- reduced binary size by splitting some Arduino core files
- reduced binary size by optimizing the pinMode() implementation
- using busybox as command shell for windows to run the wrapper scripts
- move the SPL compilation scripts into a separate project spl-splitter
- update SPL files to v2.3.0 (add support for STM8S001)
- flatten the repository structure
- update stm8gal to version 1.3.0
- updated SDCC to version 3.9/build 11242

### Fixed
- make sure main.c is pulled in for IDE builds as well
- building the core library when using make (regression bug in 0.4.0)

