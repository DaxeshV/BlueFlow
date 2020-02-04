BlueFlow
-----------
Android [Bluetooth classic](https://developer.android.com/guide/topics/connectivity/bluetooth) API wrapped in [Coroutines](https://github.com/Kotlin/kotlinx.coroutines) / [Flow](https://github.com/Kotlin/kotlinx.coroutines/blob/master/kotlinx-coroutines-core/common/src/flow/Flow.kt)
inspired by [RxBluetooth](https://github.com/IvBaranov/RxBluetooth) and [AndroidBluetoothLibrary](https://github.com/douglasjunior/AndroidBluetoothLibrary).

Dependency
------------
[![Download](https://api.bintray.com/packages/thanosfisherman/maven/blueflow/images/download.svg)](https://bintray.com/thanosfisherman/maven/blueflow/_latestVersion)

Add the following to your **app module** `build.gradle` file. Note that the respective Coroutine dependencies should also be included in the project.

```groovy
dependencies {
   implementation "io.github.thanosfisherman.blueflow:blueflow:<latest-version-number-here>"
}
```

Permissions
-------------

The following permissions must be granted for this lib to be able to work correctly.

```xml
    <uses-permission android:name="android.permission.BLUETOOTH" />
    <uses-permission android:name="android.permission.BLUETOOTH_ADMIN" />
    <uses-permission android:name="android.permission.ACCESS_COARSE_LOCATION"/>
    <uses-permission android:name="android.permission.ACCESS_FINE_LOCATION"/>
```

Usage
--------------

Coming soon! For now check the [MainActivity](https://github.com/ThanosFisherman/BlueFlow/blob/master/sample/src/main/java/io/github/thanosfisherman/blueflow/sample/MainActivity.kt) sample that demonstrates the bluetooth device discovery.

License
-------
[![License](https://img.shields.io/badge/license-Apache%202-4EB1BA.svg?style=flat-square)](https://www.apache.org/licenses/LICENSE-2.0.html)

    Copyright 2020 Thanos Psaridis

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

