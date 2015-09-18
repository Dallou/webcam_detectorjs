# Webcam_detectorjs

Webcam_detectorj is a barcode-scanner implementing Quaggajs library entirely written in JavaScript supporting real- time localization and decoding of various types of barcodes such as EAN CODE 128 and UPC-A The library is also capable of using getUserMedia to get direct access to the user's camera stream. Although the code relies on heavy image- processing even recent smartphones are capable of locating and decoding barcodes in real-time.
An extension on zxing library

# An extension of Zxing 

This is not yet another port of the great zxing library, but more of an extension to it. This implementation features a barcode locator which is capable of finding a barcode-like pattern in an image resulting in an estimated bounding box including the rotation. Simply speaking, this reader is invariant to scale and rotation, whereas other libraries require the barcode to be aligned with the viewport.

# Zxingsjs is comming soon

Cuurently, there is no equivalence of famous Zxing library in javascript but some projects try to reproduce this concept : https://github.com/wojciechszela/zxingjs
Others projects on Quaggasjs

    https://github.com/serratus/quaggaJS

