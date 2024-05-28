<!--
---
name: PCM
class: interface
type: pinout
description: BeagleY-AI PCM pins
pin:
  '8':
    name: MCASP0_ACLKR*
  '10':
    name: MCASP0_AFSR*
  '11':
    name: MCASP0_AXR2*
  '12':
    name: CLK
  '13':
    name: MCASP1_AXR1*
  '15':
    name: MCASP2_AXR14*
  '22':
    name: MCASP2_AXR15*
  '35':
    name: FS
  '36':
    name: MCASP0_AXR3*
  '37':
    name: MCASP2_AXR12*
  '38':
    name: DIN
  '40':
    name: DOUT
-->
# PCM - Pulse-code Modulation

PCM (Pulse-code Modulation) is a digital representation of sampled analog. On BeagleY-AI it's a form of digital audio output which can be understood by a DAC for high quality sound.

By default, PCM is availalbe on HW Pins 12,35,38 and 40.

(*) - BeagleY-AI provides significantly more McASP muxing options than what is normally available. 
