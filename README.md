# antenna_analyzer
Arduino graphical SWR 160-2m bands antenna analyzer based on Si5351 module

Arudino Antenna Analyzer
========================

Introduction
------------
Arudino based antenna swr analyzer / plotter can be used to measure antenna
SWR from 160m band up to 2m. The limit is around 160MHz. Next peripherals are
in use:

 * Nokia screen, PCD8544
 * Rotary controller
 * Si5351 clock generator - https://www.adafruit.com/datasheets/Si5351.pdf

Requirements:
-------------
 * Rotary - https://github.com/sh123/Rotary
 * Adafruit PCD8544 - https://github.com/adafruit/Adafruit-PCD8544-Nokia-5110-LCD-library
 * Adafruit GFX - https://github.com/adafruit/Adafruit-GFX-Library
 * Si5351 library - https://github.com/etherkit/Si5351Arduino
