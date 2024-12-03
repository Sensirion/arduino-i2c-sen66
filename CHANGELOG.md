# CHANGELOG

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased] 

## [1.0.1] - 2024-12-1

### Fixed

- Fix naming from mass concentration to number concentration for read number concentration method (returned values were correct).
## [1.0.0] - 2024-11-25

### Added

- Add all public interfaces
### Changed

- Return type of CO2 value in read_measured_values changed from float to uint16
## [0.1.0] - 2024-10-31

### Added

- Add product picture
- Add interfaces to start, stop and read measurements.
- Add interfaces to read product name, serial number and version

[Unreleased]: https://github.com/Sensirion/arduino-i2c-sen66/compare/1.0.1...HEAD
[1.0.1]: https://github.com/Sensirion/arduino-i2c-sen66/compare/1.0.0...1.0.1
[1.0.0]: https://github.com/Sensirion/arduino-i2c-sen66/compare/0.1.0...1.0.0
[0.1.0]: https://github.com/Sensirion/arduino-i2c-sen66/releases/tag/0.1.0