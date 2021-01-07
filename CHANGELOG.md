## [0.2.0] - (2021-Jan-07)

* Added dark mode.

## [0.1.9] - 

* (2020-Jan-27) Added createSplashByConfig for external usage
* (2020-Jan-05) Fix run the package command (thanks [@tenhobi](https://github.com/tenhobi))
* (2019-Oct-31) Removing comments from the example (thanks [@lucalves](https://github.com/lucalves))
* (2019-Oct-16) `image` parameter is now optional ([#26](https://github.com/henriquearthur/flutter_native_splash/issues/26))

## [0.1.8+4] - (12th October 2019)

* Fix bug on RegEx preventing `package` tag from being found in `AndroidManifest.xml` ([#25](https://github.com/henriquearthur/flutter_native_splash/issues/25))

## [0.1.8+3] - (4th October 2019)

* Prevent unhandler int exception in `color` argument (thanks [@wemersonrv](https://github.com/wemersonrv) - PR [#23](https://github.com/henriquearthur/flutter_native_splash/pull/23))

## [0.1.8+2] - (16th September 2019)

* Fix code being added multiple times to `MainActivity` ([#19](https://github.com/henriquearthur/flutter_native_splash/issues/19))

## [0.1.8+1] - (16th September 2019)

* Documentation improvements

## [0.1.8] - (16th September 2019)

* Added `fill` property to use full screen images on Android (thanks [@Bwofls2](https://github.com/Bwolfs2) - PR [#8](https://github.com/henriquearthur/flutter_native_splash/pull/8)) 
* Added `android_disable_fullscreen` property to disable opening app in full screen on Android ([#14](https://github.com/henriquearthur/flutter_native_splash/issues/14))
* Status bar color on Android is now generated dynamically by using same principles as Material Design (thanks [@yiss](https://github.com/yiss) - PR [#16](https://github.com/henriquearthur/flutter_native_splash/pull/16))

## [0.1.7+2] - (1th September 2019)

* Fix a bug on `minSdkVersion` reading ([#13](https://github.com/henriquearthur/flutter_native_splash/issues/13))

## [0.1.7+1] - (1th September 2019)

* Check for `minSdkVersion` >= 21 to add code for changing status bar color to transparent ([#12](https://github.com/henriquearthur/flutter_native_splash/issues/12))

## [0.1.7] - (27th August 2019)

* Fix a bug that duplicates entries on `Info.plist` when using multiple `</dict>` on iOS ([#5](https://github.com/henriquearthur/flutter_native_splash/issues/5))
* Fix missing imports on `MainActivity` when not using default class signature ([#7](https://github.com/henriquearthur/flutter_native_splash/issues/7))

## [0.1.6+2] - (27th August 2019)

* Yup, I released a new version because a quote was missing

## [0.1.6+1] - (27th August 2019)

* Updated README.md adding quotes on `color` property
* Add support for colors with `#` prefix

## [0.1.6] - (26th August 2019)

* Fix bug where `MainActivity` file could not be found with custom package names

## [0.1.5] - (26th August 2019)

* Add support for Kotlin
* Add support for Swift
* Add `await` to every step to create splash screen on Android and iOS to prevent async steps causing error

## [0.1.4] - (25th August 2019)

* Fix code style issues pointed by `dartanalzyer`
* Fix typo in README.md

## [0.1.3] - (25th August 2019)

* Update README.md

## [0.1.2] - (25th August 2019)

* Fix Travis CI filename


## [0.1.1] - (25th August 2019)

* Added Travis CI and updates to README.md


## [0.1.0] - (25th August 2019)

* Initial release: generate Android and iOS splash screens with a background color and an image
