# RG350 Device Layout

Pixel-perfect approximation of the RG350 device layout.

![COMPOSITE LARGE](https://user-images.githubusercontent.com/14294487/80315465-53a34880-87bd-11ea-8353-78f887f17dc0.png)

All front, top, and bottom elements of the device's layout are labeled and packaged as individual transparent PNG layer images, and the Paint.NET project file.

### FRONT
* SELECT
* START
* L3
* R3
* DPAD UP
* DPAD LEFT
* DPAD RIGHT
* DPAD DOWN
* X
* A
* Y
* B
* LED INDICATOR
* LEFT STICK
* RIGHT STICK
* LED

### TOP
* L1
* L2
* USB1
* HDMI
* HEADPHONES/AV
* USB2
* R2
* R1

### BOTTOM
* SPEAKER LEFT
* POWER
* TF
* VOLUME-
* VOLUME+
* RESET
* SPEAKER RIGHT

This project was inspired by the [RafaVico](https://github.com/RafaVico) GitHub repository for [RG350 Test](https://github.com/RafaVico/rg350_test). Version 1.3d [(OPK)](https://github.com/westoncampbell/rg350-device-layout/files/4534645/rg350test_v1.3d-opk.zip) [(ZIP)](https://github.com/westoncampbell/rg350-device-layout/files/4534646/rg350test_v1.3d-zip.zip) of RafaVico's RG350 Test application was used, extracting the images to use as the base project files. The initial source files contained compression artifacts and gradient effects to give a three-dimensional appearance, however I modified the images to use a flat color palette while adding many additional layout elements, such as RESET, TF, SPEAKERS, USB1&2, AV, HDMI, etc...

**Changelog**
---
* **Apr 26, 2020 - Revision 2**
  * Added "LED" label
  * Fixed line drawing on wrong layer image
  * Tweaked label placements
* **Apr 26, 2020 - Revision 1**
  * Initial Release
