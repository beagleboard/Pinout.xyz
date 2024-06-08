<!--
---
name: UART
class: interface
type: pinout
description: BeagleY-AI UART pins
pincount: 18
pin:
  '8':
    name: TXD / Transmit
    direction: output
    active: high
  '10':
    name: RXD / Receive
    direction: input
    active: high
  '36':
    name: CTS / Clear to Send
    direction: both
    active: high
  '11':
    name: RTS / Request to Send
    direction: both
    active: high
  '27':
    name: TXD / Transmit
    direction: output
    active: high
  '28':
    name: RXD / Receive
    direction: input
    active: high
  '3':
    name: CTS / Clear to Send
    direction: both
    active: high
  '5':
    name: RTS / Request to Send
    direction: both
    active: high
  '7':
    name: TXD / Transmit
    direction: output
    active: high
  '29':
    name: RXD / Receive
    direction: input
    active: high
  '31':
    name: CTS / Clear to Send
    direction: both
    active: high
  '26':
    name: RTS / Request to Send
    direction: both
    active: high
  '24':
    name: TXD / Transmit
    direction: output
    active: high
  '21':
    name: RXD / Receive
    direction: input
    active: high
  '19':
    name: CTS / Clear to Send
    direction: both
    active: high
  '23':
    name: RTS / Request to Send
    direction: both
    active: high
  '32':
    name: TXD / Transmit
    direction: output
    active: high
  '33':
    name: RXD / Receive
    direction: input
    active: high
-->
# UART - Universal Asynchronous Receiver/Transmitter
---
UART is an asynchronous serial communication protocol, meaning that it takes bytes of data and transmits the individual bits in a sequential fashion.

Asynchronous transmission allows data to be transmitted without the sender having to send a clock signal to the receiver. Instead, the sender and receiver agree on timing parameters in advance and special bits called 'start bits' are added to each word and used to synchronize the sending and receiving units.

UART is commonly used on the BeagleY-AI as a convenient way to control it over the GPIO, or access the kernel boot messages from the serial console (enabled by default).

It can also be used as a way to interface an Arduino, bootloaded ATmega, ESP8266, etc with your BeagleY-AI. Be careful with logic-levels between the devices though, for example the Beagle is 3.3v and the Arduino is 5v. Connecting the two without a logic level translator will damage your BeagleY-AI!