# ESP32-SI4732 Radio Receiver

The receiver was designed by a Chinese engineer. His nickname is Sunnygold and he open sourced both hardware (board, 3d-printed and cnc-machined cases) and software. Initially, he didn't knew that the receiver was sold on AliExpress and became popular on YouTube and other communities. Then another Chinese developer Zooc joined him to help improve the firmware.

The receiver uses ESP32-S3 and SI4732 and is based on the following projects:

* [FM Radio project LilyGO T-Embed ESP32 S3](https://www.youtube.com/watch?v=bg2Ysrh85Ek) ([source](https://github.com/VolosR/TEmbedFMRadio)) by Volos Projects, that uses the TEA5767 FM radio module
* [ESP32 OLED_ALL_IN_ONE](https://github.com/pu2clr/SI4735/tree/master/examples/SI47XX_06_ESP32/OLED_ALL_IN_ONE) sketch by PU2CLR (Ricardo Caratti) that uses SI4735-D60 or Si4732-A10
* [Port of ESP32 OLED_ALL_IN_ONE](https://github.com/ralphxavier/SI4735/tree/master/Lilygo_T-Display_S3/ALL_IN_ONE_T-Display_S3) by Ralph Xavier to Lilygo T-Display S3 using the [Volos interface](https://github.com/VolosR/TEmbedFMRadio)
* Open source (CC BY-NC-SA 3.0) [hardware and software](https://oshwhub.com/sunnygold/esp32s3-si4732-shou-yin-ji) (based on Ralph Xavier's work licensed under the MIT License) by Sunnygold. A copy of the attached files from oshwhub.com can be found [here](https://github.com/esp32-si4732/esp32-si4732-oshwhub). A significantly improved version of the Chinese firmware is available [here](https://github.com/zhang-chong/4732mini/).

This GitHub org was created by Max Arnold (R9UCL) and is not official in any way. It is just a collection of notes, source code, plus the excellent docs made by Dave (G8PTN). It also documents [my own fork](https://github.com/esp32-si4732/ats-mini) that is heavily based on the alernative G8PTN firmware (see the full [documentation](https://esp32-si4732.github.io/ats-mini/) here).
