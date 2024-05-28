<!--
---
name: SPI
class: interface
type: pinout
description: BeagleY-AI SPI pins
url: https://www.raspberrypi.org/documentation/hardware/raspberrypi/spi/
pincount: 5
pin:
  '8':
    name: SPI2_CLK*
  '10':
    name: SPI2_CS0*
  '11':
    name: SPI1 CE1 / SPI2_D1*
  '12':
    name: SPI1 CE0 / SPI2_CS1*
  '16':
    name: MCU_SPI1_D0*
  '18':
    name: MCU_SPI1_CS2*
  '19':
    name: SPI0 MOSI
    direction: output
    active: high
    description: Master Out / Slave In
  '21':
    name: SPI0 MISO
    direction: input
    active: high
    description: Master In / Slave Out
  '23':
    name: SPI0 SCLK
    direction: output
    active: high
    description: Clock
  '24':
    name: SPI0 CE0 
    direction: output
    active: high
    description: Chip Select 0
  '26':
    name: SPI0 CE1
    direction: output
    active: high
    description: Chip Select 1
  '29':
    name: SPI0_CS0*
  '31':
    name: SPI0_CLK*
  '32':
    name: SPI0_CS0*
  '33':
    name: SPI0_D1*
  '35':
    name: SPI1 MISO
  '36':
    name: SPI1 CE2 / SPI2 D0
  '38':
    name: SPI1 MOSI
  '40':
    name: SPI1 SCLK
-->
# SPI - Serial Peripheral Interface

---

Known as the four-wire serial bus, SPI lets you attach multiple compatible devices to a single set of pins by assigning them different chip-select pins.

To talk to an SPI device, you assert its corresponding chip-select pin.

By default the BeagleY allows you to use SPI0 with chip select pins on CE0 on GPIO 8 and CE1 on GPIO 7

**NOTE** - For compatibility reasons, BeagleY-AI uses Software SPI and Symlinks to match the Raspberry Pi. Additional HW SPI resources are available for advanced users. 