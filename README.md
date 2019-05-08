# The repo for urban sensing proejct

## Using PMS5003 (air quality sensor by the company plantower)
- PM10, PM2.5 etc.
- CUSP has Raspberry pi 3 so that we used it.
- Learned GPIO pin, serial port from raspberry pi documentation.
- VVC(5V), GND(Ground), TXD, RXD (pin usage)

## Issue
- Can't get the data from air quality sensor
- Problem was bluetooth adapter which is recognized as /dev/ttyAMA0

## Solution
- Disabled bluetooth adapter (refer to Raspberry pi Documentation)

## Referece
- [Raspberry pi Documentation](https://www.raspberrypi.org/documentation/configuration/uart.md)
- [Open energy monitor archive](https://openenergymonitor.org/forum-archive/node/12311.html)
- [Community](https://community.home-assistant.io/t/using-bluetooth-and-dtoverlay-pi3-miniuart-bt/63971)
