QR2Clip
=======

QR2Clip is an Android app that scans a QR code and copies the contents directly
to the clipboard. There is no UI. I made this because I was tired of emailing or
messaging myself links or content from my laptop that I wanted to share via SMS
or other mobile app. There are heavier-weight solutions like KDE Connect, but I
prefer something simple like this.

This repo contains the sole source file of the Android app. It depends on the
ZXing library[1] at build time and the Barcode Scanner app[2] at runtime.

[1] https://github.com/zxing/zxing
[2] https://play.google.com/store/apps/details?id=com.google.zxing.client.android
