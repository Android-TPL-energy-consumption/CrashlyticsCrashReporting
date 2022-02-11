# CrashlyticsCrashReporting

This is a minimal application, only featuring an activity with a single button. It is meant to be
cloned to study Crashlytics SDK energy consumption.

## Scenario

The `scenario.sh` script allows you to automatically browse through the application.

It will automatically launch the app, click the button (that supposedly crash the app), then tap
outside error message window, and finally, wait a few seconds for error reports to be sent.

To use it, make sure you have `adb` installed and an Android device with dev mode plugged-in.

## Configuration

Please note that only Firebase Crashlytics has been included in this application; we did not include
Google Analytics SDK in it.

## Credits

[https://github.com/rsain/Android-TPLs](https://github.com/rsain/Android-TPLs)