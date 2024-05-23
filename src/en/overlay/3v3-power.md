<!--
---
name: 3v3 Power
class: interface
type: pinout
description: BeagleY-AI 3v3 Power Pins
pincount: 2
pin:
  '1':
  '17':
-->
# 3v3 Power

BeagleY-AI generates it's 3v3 power from Buck 1 of the TPS65129 PMIC, meaning that it has up to 3.5A of current available. 

This rail is shared with other on-board peripherals such as the HDMI framer, USB hub and Ethernet PHY, so expect to have about 500mA usable. 

An external supply coupled with a 3v3 regulator is recommended for powering 3.3v projects.