## SupportMultiScreen
An Support Multi Screen for Android applications (4.0+).

[![](https://jitpack.io/v/thoaileminh/SupportMultiScreen.svg)](https://jitpack.io/#thoaileminh/SupportMultiScreen)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

An android SDK that provides a new size unit - sdp (scalable dp). This size unit scales with the screen size. It can help Android developers with supporting multiple screens.

## How to use and install SupportMultiScreen

##### Step 1. Add the JitPack repository to your build file
Add this in your root `build.gradle` file (**not** your app `build.gradle` file):

```gradle
allprojects {
    repositories {
        ...
        maven { url "https://jitpack.io" }
    }
}
```

##### Step 2. Add the library to your app `build.gradle`:

```gradle
dependencies {
    implementation 'com.github.thoaileminh:SupportMultiScreen:1.3'
    //or compile 'com.github.thoaileminh:SupportMultiScreen:1.3'
}
```


## Example usage
It's very easy to use, for example in xml file:

See the [layout_example.xml](https://github.com/thoaileminh/SupportMultiScreen/tree/master/app/src/main/res/layout/layout_example.xml) to see how to use to the sdp size unit.

![](https://raw.githubusercontent.com/thoaileminh/SupportMultiScreen/master/app/src/main/res/drawable/example.png)


## License

Copyright 2018 Lê Minh Thoại

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and limitations under the License.
