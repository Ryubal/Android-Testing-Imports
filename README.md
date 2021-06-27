# Android-Testing-Imports
Template files with the required imports to unit and UI test on Android (Java)

## Description
Whenever we want to create unit or instrumented tests, we need to include third-party software (such as Mockito, JUnit, etc). However, since most imports are static, Android Studio can have a hard time and does not import certain dependencies. Also, imports are sometimes hard to remember.

Because of this, I created this repository that includes basic imports to get you up and running with your tests.

`Note: This repository assumes that you have your testing dependencies included: JUnit, Mockito, Espresso, etc`

## Usage - Unit test
1. Create your test file
2. Open the `test/MyClassTest.java` file from this repo, and copy its contents
3. Paste the contents in your test file
4. Rename the `package` and the `MyClassTest` class name accordingly
5. Continue coding your test
6. Once your test is ready, press CTRL+ALT+O to optimize all imports. Done!

## Usage - Instrumented test
1. Create your test file
2. Open the `androidTest/MyClassTest.java` file from this repo, and copy its contents
3. Paste the contents in your test file
4. Rename the `package` and the `MyClassTest` class name accordingly
5. Continue coding your test
6. Once your test is ready, press CTRL+ALT+O to optimize all imports. Done!