# WifiMouse Android — Modernized

Community-maintained modernization of the original **WifiMouse Android App** by
Logan Krumbhaar (`krogank9`).

The goal of this project is to keep the original WifiMouse experience usable on
current Android versions while preserving the original user interface,
functionality, and communication protocol.

## Original project

- Original Android project: https://github.com/krogank9/WifiMouse
- Original Windows server: https://github.com/krogank9/WifiMouseServer
- Original author: Logan Krumbhaar (`krogank9`)

Please see `LICENSE.txt` for the original project's license.

## What has been modernized

This maintenance fork includes compatibility updates for modern Android
versions, including:

- Updated Android build configuration.
- Compatibility with current Android system behavior.
- Modern status-bar and window-inset handling.
- Fixed compatibility of the original billing dependency with newer Android
  versions.
- Fixed the keyboard remote toggle behavior on newer Android versions.
- Updated the build so the application can be built with a current Android
  toolchain.

The original UI, controls, and WifiMouse communication protocol have been
preserved.

## Compatibility

This project is intended primarily as a compatibility/maintenance update of
the original WifiMouse application.

It has been tested with the modernized Android application connecting to the
original WifiMouse Windows server.

Compatibility with every Android device, Android version, Windows configuration,
router, or network environment is not guaranteed.

## Security

WifiMouse is designed for use on a trusted local network and includes the
original password-based communication mechanism.

This project has not undergone a formal security audit. The WifiMouse server
should not be exposed directly to the public Internet.

## Building

A local Android SDK installation is required.

Clone the repository and build the debug APK with:

    ./gradlew clean assembleDebug

The generated APK will be placed under:

    app/build/outputs/apk/debug/

For a release build, configure your own signing key and build the release
variant.

## Maintenance status

This is an unofficial, independently maintained modernization, not an official new release of WifiMouse.

The primary goal is compatibility maintenance rather than redesigning the
application or adding new features.

Pull requests and improvements are welcome.

## Credits

Original WifiMouse Android application:

**Logan Krumbhaar (`krogank9`)**

This project builds upon the original WifiMouse project and retains its
original license and attribution.
