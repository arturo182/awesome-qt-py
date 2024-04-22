# Work In Progress

<h1 align="center">
  <img src="https://github.com/adafruit/awesome-qt-py/blob/main/assets/qt-py2.gif" alt="Awesome QT Py"><br>Awesome QT Py
</h1>

> A curated list of awesome Adafruit QT Py and Seeed Studio XIAO guides, hardware, software and resources.

Adafruit QT Py and Seeed Studios XIAO are microcontroller centered electronics in a small form factor. With USB connectivity on such a small package, QT Py and XIAO provide robust capabilities in a very small space.

## Contents

- [Typical Specifications](#typical-specifications)
- [Introduction and Social Media](#introduction-and-social-media)
- [Community](#community)
- [Processor Boards](#processor-boards)
- [Add-on Boards](#add-on-boards)
- [In the news](#news)
- [Videos](#videos)
- [Development](#development)
- [Contributing](#contributing)

## Typical Specifications

- Dimensions: 21.8mm x 17.8mm x 5.8mm / 0.9" x 0.7" x 0.2"
- Board pins: 14 (7x2) on a 0.1 inch spacing
- USB: USB-C Connector
- Approximate weight (depends on particular board): 2.2g / 0.1oz

## Introduction and Social Media
- [About QT Py Video Short](https://www.youtube.com/shorts/0Qssr6B6MrU)
- [Original Tutorial on the Adafruit QT Py](https://learn.adafruit.com/adafruit-qt-py)


- [Adafruit Learning System Tutorials with QT Py](https://learn.adafruit.com/search?q=QT%20py)
- [Adafruit Blog - posts on QT Py](https://blog.adafruit.com/?s=qt+py)
- [Seeed Studio Blog - posts on XIAO](https://www.seeedstudio.com/blog/?s=xiao)
- [The UF2 File Format](https://github.com/microsoft/uf2) - the drag & drop to flash disk capability.

## Community

- [/r/Adafruit QT Py Reddit](https://www.reddit.com/r/adafruit/search/?q=qt+py) 
- [QT Py on X/Twitter](https://twitter.com/search?q=qt%20py&src=typed_query)
- [Seeed XIAO on X/Twitter](https://twitter.com/search?q=seeed%20xiao&src=typed_query&f=top)
- [Adafruit Discord](https://adafru.it/discord) - Search on QT Py or XIAO

## Processor Boards

### Adafruit QT Py Processor Boards

| Name | Processor | CircuitPython | Arduino | Wireless | Features |
|--------------------|------------------|---|---|---|---------------------------------|
| [QT Py RP2040](https://www.adafruit.com/product/4900) | RP2040 | Yes | Yes | No | Stemma QT I2C Port |
| [QT Py ESP32 Pico](https://www.adafruit.com/product/5395) | ESP32 Pico V3 02 | MicroPython | Yes | WiFi+BLE+BT | 8MB Flash, 2MB PSRAM, Stemma QT Port |
| [QT Py ESP32-C3 WiFi](https://www.adafruit.com/product/5405) | ESP32-C3 | MicroPython | Yes | WiFi | Stemma QT I2C Port |
| [QT Py ESP32-S2](https://www.adafruit.com/product/5325) | ESP32-S2 | Yes | Yes | WiFi | 4MB Flash, 2MB PSRAM, Stemma QT I2C, chip antenna |
| [QT Py ESP32-S2](https://www.adafruit.com/product/5348) | ESP32-S2 | Yes | Yes | WiFi | 4MB Flash, 2MB PSRAM, Stemma QT I2C, uFL antenna connector |
| [QT Py S3](https://www.adafruit.com/product/5700) | ESP32-S3 | Yes | Yes | WiFi+BLE | 2MB PSRAM, Stemma QT Port
| [QT Py ESP32-S3](https://www.adafruit.com/product/5426) | ESP32-S3 | Yes | Yes | WiFi+BLE | 8MB Flash, NO PSRAM, Stemma QT |
| [QT Py - SAMD21](https://www.adafruit.com/product/4600) | ATSAMD21E18 | Yes | Yes | No | Stemma QT I2C Port |

### Seeed Studio XIAO Processor Boards

| Name | Processor | CircuitPython | Arduino | Wireless | Features |
|--------------------|------------------|---|---|---|---------------------------------|
| [XIAO ESP32C3](https://www.seeedstudio.com/Seeed-XIAO-ESP32C3-p-5431.html) | ESP32-C3 | Yes | Yes | WiFi | u.FL Antenna |
| [XIAO ESP32C6](https://www.seeedstudio.com/Seeed-Studio-XIAO-ESP32C6-p-5884.html) | ESP32-C6 | No | Yes | WiFi6+BLE+802.15.4 | Zigbee/Thread Support |
| [XIAO nRF52840](https://www.seeedstudio.com/Seeed-XIAO-BLE-nRF52840-p-5201.html) | nRF52840 | Yes | Yes | WiFi+BLE | Chip Antenna |
| [XIAO nRF52840 Sense](https://www.seeedstudio.com/Seeed-XIAO-BLE-Sense-nRF52840-p-5253.html) | nRF52840 | Yes | Yes | WiFi+BLE | Microphone and 6-DOF IMU |
| [XIAO RP2040](https://www.seeedstudio.com/XIAO-RP2040-v1-0-p-5026.html) | RP2040 | Yes | Yes | No | NeoPixel LED |
| [XIAO SAMD21](https://www.seeedstudio.com/Seeeduino-XIAO-Arduino-Microcontroller-SAMD21-Cortex-M0+-p-4426.html) | ATSAMD21G18 | Yes | Yes | No |    |
| [XIAO ESP32S3](https://www.seeedstudio.com/XIAO-ESP32S3-p-5627.html) | ESP32-S3 | No | Yes | WiFi+BLE | Chip + u.FL Antenna |
| [XIAO ESP32S3 Sense](https://www.seeedstudio.com/XIAO-ESP32S3-Sense-p-5639.html) | ESP32-S3 | No | Yes | WiFi+BLE | Camera, Microphone, u.FL Antenna |

## Add-on Boards

Adafruit calls their QT Py size add-on boards "BFF"

| Company | Name  | Features |
|---|---|---|
| Adafruit | [EYESPI BFF for QT Py or Xiao](https://www.adafruit.com/product/5772) | 18 Pin EYESPI FPC Connector for connecting displays |
| Adafruit | [microSD Card BFF Add-On for QT Py and Xiao](https://www.adafruit.com/product/5683) | Provides a microSD card slot |
| Adafruit | [Audio BFF Add-on for QT Py and Xiao](https://www.adafruit.com/product/5769) | MAX98357 3 watt audio amplifier, microSD slot, connector for speaker |
| Adafruit | [NeoKey BFF for Mechanical Key Add-On](https://www.adafruit.com/product/5695) | Add a Cherry MX compatible switch |
| Adafruit | [BNO055 + BMP280 BFF Add-On for QT Py](https://www.adafruit.com/product/5937) | 9 degree-of-freedom (9DoF) motion plus pressure/altitude sensing |
| Adafruit | [DC Power BFF Add-On for QT Py](https://www.adafruit.com/product/5882) | Power a QT Py or XIAO up to 20 volts DC |
| Adafruit | [CAN Bus BFF Add-On for QT Py](https://www.adafruit.com/product/5877) | MCP26525 CAN controller+transceiver and connector |
| Adafruit | [NeoPixel Driver BFF Add-On for QT Py and Xiao](https://www.adafruit.com/product/5645) | Level shift signal to 5V for NeoPixel LED driving |
| Adafruit | [I2S Amplifier BFF Add-On for QT Py and Xiao](https://www.adafruit.com/product/5770) | MAX98357 audio amplifier and picoblade speaker connector |
| Adafruit | [5x5 NeoPixel Grid BFF Add-On for QT Py and Xiao](https://www.adafruit.com/product/5646) | 25 (5x5) small RGB LEDs |
| Adafruit | []() |  |
| Adafruit | []() |  |
| Adafruit | []() |  |

## News
- [Tom's Hardware Best RP2040 Boards 2024](https://www.tomshardware.com/best-picks/best-rp2040-boards) - Adafruit QT Py Rp2040 and Seeed XIAO RP2040, April 3, 2024
- [Adafruit QT Py RP2040 Review: A tiny board for great projects](https://www.tomshardware.com/reviews/adafruit-qt-py-rp2040-review) - by Les Pounder, April 18, 2021

## Videos

### QT Py

- [hackster.io QT Py Unboxing](https://www.hackster.io/videos/769)
- [QT Py Videos on YouTube](https://www.youtube.com/results?search_query=qt+py)
- [Adafruit QT Py - tiny but mighty](https://www.youtube.com/watch?v=dAYrv1azfT4)
- [First Look at the Adafruit QT Py RP2040 - Fantastic Tiny RP2040 Board](https://www.youtube.com/watch?v=qfbPyu_1L18)
- [Adafruit QT PI SAMD21 Board](https://www.youtube.com/watch?v=qwKIxXVd0lc)
- [The first ESP32-C3 QT Py off the machine line](https://www.youtube.com/watch?v=whaBOyJfLSM)

XIAO

- [Seeeduino XIAO the Smallest Arduino, Getting Started Tutorial, Pinout, specifications, & Arduino IDE](https://www.youtube.com/watch?v=t1XsDqZjuQo)
- [ESP32-C3 XIAO, the Smallest ESP32 Board, ESP32-C3 by Seeed Studio, XIAO ESP32-C3](https://www.youtube.com/watch?v=P215DJxGjQs)
- [XIAO ESP32C6 Getting Started Tutorial, Seeed Studio, Smallest ESP32](https://www.youtube.com/watch?v=LnFYCHeL84w)
- [Seeeduino XIAO - 32-bit Arduino-compatible Microcontroller](https://www.youtube.com/watch?v=pTwEnckaPYY)
- [Unboxing and testing the Seeedstudio XIAO nerdhut.de](https://www.youtube.com/watch?v=oqDOyln_4dE)
- [Seeed XIAO RP2040](https://www.youtube.com/watch?v=u61mOIfGdR8)

## Development


## Contributing

Contributions and suggestions are always welcome! Please make GitHub pull requests to modify Awesome QY Py.

## License & Trademarks

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the authors have waived all copyright and related or neighbouring rights to this work.
