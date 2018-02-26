# ili9486

ILI9486 drivers for [Waveshare 3.5inch TFT LCD](http://www.waveshare.com/product/3.5inch-RPi-LCD-A.htm) and clones.

Implementation of simple drivers for ILI9486 display.
**stm32f4** folder contains bare metal C driver for STM32F4 (tested on STM32F4 - NUCLEO-F446RE), while **raspberry-pi** Python driver for Raspberry Pi (tested on Raspberry Pi 2 Model B) - this Python driver was developed for simple testing, it was quickly created, but it is running quite slow.

Useful links
------------

- [Datasheet](http://www.datasheet-pdf.com/PDF/ILI9486-Datasheet-ILITEK-945603)
- [Linux FBTFT driver](https://github.com/notro/fbtft)
- [Waveshare overlays](https://github.com/swkim01/waveshare-dtoverlays)
- [STlink Linux](https://github.com/texane/stlink)
- [Arduino UTFT library](http://www.rinkydinkelectronics.com/library.php?id=51)
- STM32 Discovery for Linux
  - [Development](http://www.wolinlabs.com/blog/linux.stm32.discovery.gcc.html)
  - [Source](https://github.com/rowol/stm32_discovery_arm_gcc)

