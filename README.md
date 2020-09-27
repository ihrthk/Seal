<img src="./seal-banner.png" alt="Seal" width="359px">

[![Download](https://api.bintray.com/packages/2bab/maven/seal/images/download.svg)](https://bintray.com/2bab/maven/seal/_latestVersion) [![Hex.pm](https://img.shields.io/hexpm/l/plug.svg)](https://www.apache.org/licenses/LICENSE-2.0)

Seal is a gradle plugin to do precheck of Android Manifest. 

English | [中文说明](/README_zh.md)


## Why use DOM parser API

[Oracle Comparing StAX to Other JAXP APIs](https://docs.oracle.com/javase/tutorial/jaxp/stax/why.html#bnbea)

Since we need to support "Tag delete" feature, and export outputs quickly, from the link above we can know DOM is easiest one to process that. Though it consumes more CPU and memory resources, luckily most of `AndroidManifest.xml` are not complex and with the help of Gradle we can cache the task result if those input(s) didn't change.




## License

    Copyright 2017-2020 2BAB

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

