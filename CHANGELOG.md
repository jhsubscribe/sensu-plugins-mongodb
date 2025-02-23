#Change Log
This project adheres to [Semantic Versioning](http://semver.org/).

This CHANGELOG follows the format listed at [Keep A Changelog](http://keepachangelog.com/)

## Unreleased
### Fixed
- Stopped trying to gather indexCounters data from mongo 3 (metrics-mongodb.rb)

## [0.0.6] - 2015-10-13
### Fixed
- Rename option to avoid naming conflict with class variable name
- Add message for replica set state 9 (rollback)
- Installation fix

## [0.0.5] - 2015-09-04
### Fixed
- Fixed non ssl mongo connections

## [0.0.4] - 2015-08-12
### Changed
- general gem cleanup
- bump rubocop

## [0.0.3] - 2015-07-14
### Changed
- updated sensu-plugin gem to 1.2.0

## [0.0.2] - 2015-06-03
### Fixed
- added binstubs

### Changed
- removed cruft from /lib

## 0.0.1 - 2015-05-20
### Added
- initial release

[unreleased]: https://github.com/sensu-plugins/sensu-plugins-mongodb/compare/0.0.4...HEAD
[0.0.4]: https://github.com/sensu-plugins/sensu-plugins-mongodb/compare/0.0.3...0.0.4
[0.0.3]: https://github.com/sensu-plugins/sensu-plugins-mongodb/compare/0.0.2...0.0.3
[0.0.2]: https://github.com/sensu-plugins/sensu-plugins-mongodb/compare/0.0.1...0.0.2
