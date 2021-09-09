# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Added
- Support GitKraken v7.7.2
- Added maintainers to info on logo

### Changed
- Splitted patches for version ***>=7.x && <=7.5.x*** and ***>=7.6.x*** (thanks to @ductran95)
- Use TypeScript's `resolveJsonModule` option to load packages.json instead using `fs-extra` Npm package

## [v0.9] - 2020-11-12
### Added
- Support GitKraken v7.4.0

## [v0.8] - 2020-02-26
### Added
- Support GitKraken v6.5.3
- Added short flags for command-line options

### Changed
- Set same default actions (`backup`, `unpack`, `patch`, `pack` and `remove`) for all platforms (Win, Linux, Mac)
- Other minor fixs

## [v0.7] - 2020-02-11
### Changed
- Synchronized all forks

## [v0.6.1] - 2019-07-30
### Changed
- Support GitKraken v6.0.0
  - Pro
  - Individual
  - Enterprise
    - Self-Hosted
    - Stand-Alone
  - Modes
    - Development
    - Staging
- Bump dependencies

## [v0.6.0] - 2018-01-08
### Added
- Support GitKraken Pro v6.0.0
- Bump dependencies

[Unreleased]: https://github.com/BoGnY/GitCracken/compare/v0.9...HEAD
[v0.9]: https://github.com/BoGnY/GitCracken/compare/v0.8...v0.9
[v0.8]: https://github.com/BoGnY/GitCracken/compare/v0.7...v0.8
[v0.7]: https://github.com/BoGnY/GitCracken/compare/v0.6.1...v0.7
[v0.6.1]: https://github.com/BoGnY/GitCracken/compare/v0.6.0...v0.6.1
[v0.6.0]: https://github.com/BoGnY/GitCracken/releases/tag/v0.6.0
