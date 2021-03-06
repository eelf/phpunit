# Changes in PHPUnit 5.2

All notable changes of the PHPUnit 5.2 release series are documented in this file using the [Keep a CHANGELOG](http://keepachangelog.com/) principles.

## [5.2.0] - 2016-02-05

### Added

* Implemented [#1902](https://github.com/sebastianbergmann/phpunit/issues/1902): Mark a test as risky when it performs an assertion on a test double
* Implemented [#1905](https://github.com/sebastianbergmann/phpunit/issues/1905): Add `--fail-on-risky` and `--fail-on-warning` commandline options as well as `failOnRisky` and `failOnWarning` configuration options
* Implemented [#1912](https://github.com/sebastianbergmann/phpunit/issues/1912): Add support for specifying the extension version with the `@requires` annotation
* Implemented [#1977](https://github.com/sebastianbergmann/phpunit/issues/1977): Add support for disabling annotations that control the ignoring of code coverage

[5.2.0]: https://github.com/sebastianbergmann/phpunit/compare/5.1...5.2.0

