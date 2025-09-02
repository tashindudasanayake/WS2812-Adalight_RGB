# WS2812 Adalight Test (Arduino)

This project uses an Arduino to drive 36 WS2812 RGB LEDs with the Adalight protocol.  
Compatible with Boblight / Prismatik.  

## Hardware
- Arduino Uno / Nano
- 36x WS2812 LEDs
- Data pin: D6

## How it works
- Arduino listens for "Ada" magic word over serial.
- Colors are sent via Prismatik software and displayed on LEDs.

