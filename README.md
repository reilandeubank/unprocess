unprocess
===========================

This project is based on https://github.com/android/camera-samples/tree/main/Camera2Basic and is a
simple, open source solution to taking unprocessed images on your Android phone, free of
modern devices' excessive computational photography.

Introduction
------------

unprocess uses the [Camera2 API][1] to capture raw sensor data from the camera before being
converted to a human-viewable file format.

Currently, unprocess allows users to choose between RAW (.dng) or JPEG (.jpg) for the final,
saved file. The images are captured in the same way, but in the latter case the raw data is
converted from RAW to bitmap data before being compressed into a JPEG.

[1]: https://developer.android.com/reference/android/hardware/camera2/package-summary.html

Pre-requisites
--------------

- Android SDK 29+
- Android Studio 3.5+

Screenshots
-------------

None at the moment

Getting Started
---------------

This sample uses the Gradle build system. To build this project, use the
"gradlew build" command or use "Import Project" in Android Studio.

Support
-------

Patches are encouraged, and may be submitted by forking this project and
submitting a pull request through GitHub.

This is my first foray into Android app development, so the project may start a little rough
around the edges. If there is community interest, I will do my best to keep it going and
take in any improvements that are able to be contributed. I can be contacted at my email
(reilandeubank@proton.me) or various social medias with the username @reilandeubank.