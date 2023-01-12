# U8g2-teensy41 

U8g2-teensy41 is a repository to hold my simple edits to enable SPI2 support on Teensy4.1, and possibly my future edits to make these changes upstream-worthy.

Users are urged to stick with the original U8g2 repository for the latest version and support unless you need this specific SPI2 support as well.  I'm just tweaking some constructors to use the `SPI2` object instead of `SPI` so I can plug the screen into different pins.

Original README.md continues below.

---

# U8g2_Arduino: Arduino Monochrome Graphics Library

![https://raw.githubusercontent.com/wiki/olikraus/u8g2/img/uc1701_dogs102_uno_board_320.jpg](https://raw.githubusercontent.com/wiki/olikraus/u8g2/img/uc1701_dogs102_uno_board_320.jpg) 

U8glib V2 library for Arduino

Description: https://github.com/olikraus/u8g2/wiki

Issue Tracker: https://github.com/olikraus/u8g2/issues

Download (2.33.15): https://github.com/olikraus/U8g2_Arduino/archive/master.zip

