# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic
Versioning](https://semver.org/spec/v2.0.0.html).

## [2.0.0] - 2026-03-18

### Added

* Embedded Italian word list from [Tarin Gamberini](http://www.taringamberini.com).
* CamelCase output option (`--cli` / `-c` flag, `with_camel_case()` API).

### Changed

* **BREAKING** Refactored API to use a builder pattern (`Config::new().with_xxx()`) instead of positional constructor arguments.
* Removed digits from the special character set.

## [1.0.2] - 2022-09-04

### Changed

* Update the dependencies.
* Update to Rust 2021.
* Refactor some code.
* Split the CLI and library in two packages.
* [CLI] Colorise error messages when colors are supported.

## [1.0.1] - 2018-05-30

### Changed

* Update the code to use Rust 1.26 features.
* Update the dependencies.

## [1.0.0] - 2018-04-07

### Added

* Initial version with English and French embedded word lists.

[2.0.0]: https://github.com/ejpcmac/diceware/compare/v1.0.2...v2.0.0
[1.0.2]: https://github.com/ejpcmac/diceware/compare/v1.0.1...v1.0.2
[1.0.1]: https://github.com/ejpcmac/diceware/compare/v1.0.0...v1.0.1
[1.0.0]: https://github.com/ejpcmac/diceware/releases/tag/v1.0.0
