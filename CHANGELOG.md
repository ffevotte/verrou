# Change Log

All notable changes between released versions of this project should be
documented here.

This project adheres to [Semantic Versioning](http://semver.org/).



## [UNRELEASED]

This version is based on Valgrind-3.12.0.

### Added

- Continuous integration using the Travis system.
- Improve Delta-Debugging customization through environment variables.

### Changed

- There is no need anymore for an external, statically compiled libc/libm.


---

## v0.9.0 - 2017-03-31

This is the first released version of Verrou. It is based on Valgrind-3.10.1,
which supports the following system configurations:

- `gcc`, versions 3.x to 5.x
- `clang`, versions 2.9 to 4.x
- `glibc`, versions 2.2 to 2.20
