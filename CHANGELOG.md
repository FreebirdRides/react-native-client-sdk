# Changelog

All notable changes to the LaunchDarkly React Native SDK will be documented in this file. This project adheres to [Semantic Versioning](http://semver.org).

## [2.0.1] - 2019-06-27
### Fixed
- Listeners on Android now have the proper event emitter key and work properly.
- Flag values in the object returned by `allFlags`  will no longer be Strings when they should be JSON Objects on Android.

### Changed
- Updated Android Client SDK to version 2.8.5
- Updated iOS Client SDK to version 4.1.2

## [2.0.0] - 2019-06-27
### Fixed
- Changes polling mode to not be ignored in config.

### Changed
- Updated Android Client SDK to version 2.8.4
- Updated iOS Client SDK to version 4.1.0
- Updated React Native to version 0.59.9 and updated React to version 16.8.3
- Updated to allow usage with Xcode 10.2.1
- Updated Swift to version 5.0

 This is a major version because of breaking version updates.

## [1.0.1] - 2019-05-03
### Changed
- Changed the package name from `launchdarkly-react-native-client` to `launchdarkly-react-native-client-sdk`
- Changed repository references to use the new URL

There are no other changes in this release. Substituting `launchdarkly-react-native-client` version 1.0.0 with `launchdarkly-react-native-client-sdk` version 1.0.1 will not affect functionality.

## [1.0.0] - 2019-04-18
### Changed
- Android and iOS client versions
### Fixed
- Added correct anonymous property
- Removed dependencies and added caret to peer dependencies

### Note on future releases

The LaunchDarkly SDK repositories are being renamed for consistency. This repository is now `react-native-client-sdk` rather than `react-native-client`.

The package name will also change. In the 1.0.0 release, it is still `launchdarkly-react-native-client`; in all future releases, it will be `launchdarkly-react-native-client-sdk`.

## [1.0.0-beta.1] - 2019-03-01
### Added
- CHANGELOG.md and CONTRIBUTING.md
### Changed
- Moved `LaunchDarklyReactNativeClient.podspec` into `ios/`
### Fixed
- Changed `config.yml` to run against `hello-react-native`.
