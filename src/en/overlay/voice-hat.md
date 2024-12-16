<!--
---
name: AIY Voice HAT
page_url: voice_hat
class: board
type: audio,sensor,io
formfactor: HAT
manufacturer: Google
description: A natural language processor that connects your Raspberri Pi to the Google Assistant
url: https://aiyprojects.withgoogle.com/voice-v1
github: https://github.com/google/aiyprojects-raspbian
image: 'voice-hat.png'
pincount: 40
eeprom: yes
power:
  '1':
  '2':
ground:
  '6':
  '9':
  '14':
  '20':
  '25':
  '30':
  '34':
  '39':
pin:
  '7':
    name: Driver 0 Breakout
  '11':
    name: Driver 1 Breakout
  '12':
    name: I2S Clock
  '13':
    name: Driver 2 Breakout
  '15':
    name: Driver 3 Breakout
  '16':
    name: Button
    mode: input
    active: low
  '18':
    name: Servo 5 Breakout
  '22':
    name: LED
    mode: output
    active: high
  '29':
    name: Servo 3 Breakout
  '31':
    name: Servo 1 Breakout
  '32':
    name: Servo 4 Breakout
  '33':
    name: Servo 2 Breakout
  '35':
    name: I2S WS
  '36':
    name: Amp Shutdown
  '37':
    name: Servo 0 Breakout
  '38':
    name: I2S Data Input
  '40':
    name: I2S Data Output
install:
  'devices':
  - 'i2s'
-->
# AIY Voice HAT

The AIY Voice HAT connects the BeagleY-AI to the Google Assistant and is part of Google's AIY Voice Kit V1. It was created with the Raspberry Pi 3 Model B in mind but may be used with any single board computer featuring a 40-way header.

The HAT includes on-board hardware to facilitate audio capture and playback, connectors for the dual mic daughter board and speaker, GPIO breakouts to connect low-voltage components like micro-servos and sensors, and an optional barrel connector for dedicated power supply.

For specific instructions on adapting the HAT to be compatible with the BeagleY-AI, visit this [article](https://medium.com/@s-kodiganti/designing-a-smart-assistant-with-beagley-ai-139d0451cd15) or this [demonstration video](https://www.ti.com/video/6360515319112). 