# NodeMCU ESP8266 How-To

> Quick start information on programming [ESP8266](https://www.espressif.com/en/products/hardware/esp8266ex/overview) in [NodeMCU](https://github.com/nodemcu/nodemcu-firmware) environment

## Quick Start to Hello World

Get me to the Hello World as quick as possible -> [RUN](quick-start-helloworld.md)

For something more interesting try [Wi-Fi Detector](examples/wifi_detector)

## Documentation

[Official NodeMCU documentation](https://nodemcu.readthedocs.io/en/master/) is good and if you want to understand the details you should go and read it completely. This repository contains some distilled and often biased quick lookup information on the topic.

## Main Tools

- [nodemcu-tool](nodemcu-tool.md)
- [esptool.py](esptool.md)
- [docker-nodemcu-build](docker-nodemcu.md)
- [Lua](https://www.lua.org/) programming language
- (optional) [nodemcu-build](https://nodemcu-build.com/)

### Related tools

- [Python](https://www.python.org/) + [pip](https://pypi.org/project/pip/)
- [Node.js](https://nodejs.org) + [Npm](https://www.npmjs.com/)
- [Docker](https://www.docker.com/)

## USB Drivers

You may need to install a driver in order to be able to communicate with your ESP8266 module over USB. It depends on a specific USB-UART converter chip, but you most probably will see one of those below:

- CH340G - [drivers](https://sparks.gogo.co.nz/ch340.html)
- CP2102 - [drivers](https://www.silabs.com/products/development-tools/software/usb-to-uart-bridge-vcp-drivers)

For more detailed information look at [Drivers](usb-uart-drivers.md) page
