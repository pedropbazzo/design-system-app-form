<p align="center"><img src="logo.jpeg"></p>

<p align="center">
<a href="https://github.com/TheJuki/KFormMaster/actions"><img src="https://github.com/TheJuki/KFormMaster/workflows/Build/badge.svg?branch=master" alt="Build status" /></a>
<a href="https://codecov.io/gh/TheJuki/KFormMaster"><img src="https://codecov.io/gh/TheJuki/KFormMaster/branch/master/graph/badge.svg" alt="codecov" /></a>
<a href="https://codebeat.co/projects/github-com-thejuki-kformmaster-master"><img alt="codebeat badge" src="https://codebeat.co/badges/43fca492-2564-4401-8f4b-91d3bc811d70" /></a>
<a href="https://android-arsenal.com/api?level=19"><img src="https://img.shields.io/badge/API-19%2B-brightgreen.svg?style=flat" alt="API" /></a>
<a href="https://android-arsenal.com/details/1/6761"><img src="https://img.shields.io/badge/Android%20Arsenal-KFormMaster-brightgreen.svg?style=flat" border="0" alt="Android Arsenal"></a>
<a href="https://bintray.com/thejuki/maven/k-form-master/_latestVersion"><img src="https://api.bintray.com/packages/thejuki/maven/k-form-master/images/download.svg" alt="Download" /></a>
</p>


## Examples
| [Full Screen](https://github.com/TheJuki/KFormMaster/blob/master/app/src/main/java/com/thejuki/kformmasterexample/FullscreenFormActivity.kt) | [Partial Screen](https://github.com/TheJuki/KFormMaster/blob/master/app/src/main/java/com/thejuki/kformmasterexample/PartialScreenFormActivity.kt) | [Login](https://github.com/TheJuki/KFormMaster/blob/master/app/src/main/java/com/thejuki/kformmasterexample/LoginFormActivity.kt) |
| --- | --- | --- |
![Example](https://github.com/TheJuki/KFormMaster/blob/master/screenshots/full-screen-form.gif) | ![Example](https://github.com/TheJuki/KFormMaster/blob/master/screenshots/partial-screen-form.gif) | ![Example](https://github.com/TheJuki/KFormMaster/blob/master/screenshots/login.gif) |

## Java Compatibility
- This library was ported from Java and is still compatible with Java code

## Installation
Add this in your app's **build.gradle** file:
```
ext {
  kFormMasterVersion = [Latest]
}

implementation "com.pedropbazzo:design-system-app-form:$kdesign-system-app"
```

Add this to your root **build.gradle** file:
```
allprojects {
    repositories {
        google()
        jcenter()
        maven { url "https://jitpack.io" }
    }
}
```

## Version 6 Changes
- Removed Form Element Builder Classes
- Migration Guide: https://thejuki.github.io/KFormMaster/migrateBuilder/

## BrowserStack
<a href="http://browserstack.com/">
<img src="browserstack-logo-600x315.png" alt="BrowserStack" width="200px"/>
</a>

The App Automate feature of BrowserStack is used for Espresso testing of this library. The App Automate REST API is used to upload the example app and test app to test multiple devices in parallel.


License
-----------------
This library is available as open source under the terms of the [Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0).
