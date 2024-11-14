# Changelog

## [1.3.1] - 2024-11-14
### Changed
- Removed some noisy rules about comments.
- Changed severity to warning for rules about naming conventions, missing translators comments and empty catch statements.

## [1.3.0] - 2023-12-21
### Added
- Added WooCommerce sanitization and escaping functions to whitelist in security rules.

## [1.2.8] - 2023-09-14
### Added
- Whitelisted some of WooCommerce custom capabilities for sniffs.
### Changed
- Removed sniff for unescaped exceptions.

## [1.2.7] - 2023-08-28
### Changed
- Updated WPCS upstream version to 3.0

## [1.2.6] - 2023-05-30
### Fixed
- Changed excluded ruleset reference according to upstream update

## [1.2.5] - 2023-05-30
### Changed
- Updated wp-code-sniffer/wpcs to `dev-develop` as tagged version is outdated

## [1.2.4] - 2023-04-24
### Changed
- Updated dependent packages

## [1.2.3] - 2021-07-07
### Changed
- Removed demanding brackets with inline if statement

## [1.2.2] - 2021-06-16
### Changed
- Add phpcs.xml.dist and .editorconfig to package distribution as configuration examples to copy

## [1.2.1] - 2021-06-14
### Fixed
- Removed wrapping operations in brackets

## [1.2.0] - 2021-06-14
### Changed
- Fully rewritten CS rules to adhere developers needs
- Enhanced .editorconfig to work seamlessly with PhpStorm

### Removed
- Unnecessary files and folders belonging to other project

## [1.1.0] - 2021-05-21
### Added
- Support for Composer 2
- Support for PHP 8

## [1.0.1] - 2019-05-30
### Added
* classes directory in rules

## [1.0.0] - 2019-05-30
### Added
* First version
