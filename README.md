# ClassyShark

### Introduction

Follow the shark on twitter [@ItsClassyshark](https://twitter.com/ItsClassyshark)

ClassyShark is a standalone tool for Android developers. It can reliably browse any Android executable and show important info such as class interfaces and members, dex counts and dependencies. ClassyShark supports multiple formats including libraries (.dex, .aar, .so), executables (.apk, .jar, .class) and all Android binary xmls: AndroidManifest, resources, layouts etc'.

### Useful links
* [User guide] (https://github.com/borisf/classyshark-user-guide)
* [Command-line reference] (https://github.com/google/android-classyshark/blob/master/CommandLine.pdf)
* Gradle [sample](https://github.com/google/android-classyshark/tree/master/Samples/SampleGradle) 

### Download

To run, grab the latest jar from [here] (https://github.com/google/android-classyshark/releases)
and type `java -jar ClassyShark.jar`.

### Dependencies
* [dexlib2](https://github.com/JesusFreke/smali/tree/master/dexlib2) by jesusfreke
* [guava](https://github.com/google/guava) by Google
* [ASM](http://asm.ow2.org/) by OW2
* [ASMDEX](http://asm.ow2.org/asmdex-index.html) by OW2
* [java-binutils](https://github.com/jawi/java-binutils) by jawi
* [BCEL](https://commons.apache.org/proper/commons-bcel) by Apache

### Support
If you've found an error, please file an issue:

https://github.com/google/android-classyshark/issues

Patches are encouraged, and may be submitted by forking this project and
submitting a pull request through GitHub.

License
=======

    Copyright 2016 Google, Inc.

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.



