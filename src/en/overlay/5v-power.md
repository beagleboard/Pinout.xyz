<!--
---
name: 5v Power
class: interface
type: pinout
description: BeagleY-AI 5v Power Pins
pincount: 2
pin:
  '2':
  '4':
-->
# 5v Power

The 5v power pins are connected directly to the BeagleY-AI power input and will capably provide the full supply current of your mains adapter, minus that used by the BeagleY-AI itself.

With a decent USB-C PD power supply, you can expect to pull about 1.5A depending on peripheral load. Devices that require high current - such as LED panels, long LED strips or motors - should use an external power supply.
