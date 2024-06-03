<!--
---
name: MCU
class: interface
type: pinout
description: BeagleY-AI MCU Domain pins
pin:
  '3':
    name: MCU_I2C0_SDA
    direction: both
    active: high
  '5':
    name: MCU_I2C0_SCL
    direction: both
    active: high
  '16':
    name: MCU_UART0_CTSn
    direction: both
    active: high
  '18':
    name: MCU_SPI1_CS2
    direction: both
    active: high
  '19':
    name: MCU_SPI0_D0
    direction: both
    active: high
  '21':
    name: MCU_SPI0_D1
    direction: both
    active: high
  '23':
    name: MCU_SPI0_CLK
    direction: both
    active: high
  '24':
    name: MCU_SPI0_CS0
    direction: both
    active: high
  '26':
    name: MCU_SPI0_CS2
    direction: both
    active: high
-->
# MCU - R5 Microcontroller Subsystem Pins

The AM67A SoC Inside BeagleY-AI also features R5 MCU cores which are able to act independently of the Cortex A53 which normally run Linux. 

You can use the R5 MCU to run Zephyr, MicroPython and much more without having to worry* about what other parts of the system are doing!

The pins shown in this section are connected directly to the MCU cores, however, you can control any system pin from any core at the expense of some small amount of latency. 