## 0.4.1 - 19 July 2019

  * Update docs to specify correct version for Flutter
    - For Flutter 1.7.x with Dart 2.4, use version `0.3.0`
    - For Flutter 1.8.x+ with Dart 2.5, use version `0.4.0` or higher

## 0.4.0 - 18 July 2019

  * Proper Fix for latest Dart 2.5 & Flutter 1.8.x -- use `Uint8List` instead of `List<int>`

## 0.3.0 - 16 July 2019

  * Fix missing `compressionState` error.

## 0.2.2 - 10 Nov 2018

* Bugfix: Show correct request headers when using http client

## 0.2.1 - 19 Oct 2018

* Bugfix: Imports were broken

## 0.2.0 - 19 Oct 2018

* BREAKING CHANGE: Use `Stetho.initialize()` instead of overriding the HTTP Client!
* This allows us to initialize the Android code only when `Stetho.initialize()` is invoked, rather than running Stetho by default, which is bad for production builds.
* More work to be done on stripping the plugin from the APK during production builds. Flutter issue opened.

## 0.1.2 - 17 Aug 2018

* Fix `connectionTimeout`. Thanks @pcqpcq!

## 0.1.1 - 27 Apr 2018

* Fix docs

## 0.1.0 - 27 Apr 2018

* Fix for Dart 2. Thanks @thejakeofink!

## 0.0.1 - 4 Mar 2018

* Initial version, with support for network inspection on Android via the Chrome Dev Tools using Stetho
