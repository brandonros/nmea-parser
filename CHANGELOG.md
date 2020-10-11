# Changelog

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]
### Added
- Implementation of AIS VDM/VDO type 4 message
### Changed

## [0.3.1] - 0202-10-09
### Changed
- Fixed the example program in README.md

## [0.3.0] - 0202-10-09
### Added
- Added `ParseError` type

### Changed
- Renamed `gnss::*::system` field to `gnss::*::source`
- Changed `parse_sentence` to return `ParseError` instead of plain `String` in case of errors
- Renamed `RmcData::speed_knots` to `RmcData::sog_knots`
- Renamed `gnss` module's structs and enums to make them more consistent
- Refactored the whole module hierarchy to improve modularity and clarity
- Improved the example program

## [0.2.0] - 2020-10-08
### Changed
- Renamed `decode_sentence` to `parse_sentence` 

## [0.1.1] - 2020-10-07
### Added
- Missing code gneration script `mid-to-iso3166.py` added
### Changed
- Minor refactoring and documentation corrections

## [0.1.0] - 2020-10-07
### Added
- Initial release
