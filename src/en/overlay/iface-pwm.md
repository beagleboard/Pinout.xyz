<!--
---
name: PWM
class: interface
type: pinout
description: BeagleY-AI PWM pins
pin:
  '8':
    name: EHRPWM0*
  '10':
    name: EHRPWM0*
  '11':
    name: ECAP2*
  '12':
    name: PWM0
  '29':
    name: EHRPWM0*
  '31':
    name: EHRPWM1*
  '32':
    name: PWM0
  '33':
    name: PWM1
  '35':
    name: PWM1
  '36':
    name: ECAP1*
  '38':
    name: EHRPWM1*
  '40':
    name: EHRPWM1*
-->
# PWM - Pulse-width Modulation

PWM (Pulse-width Modulation) is a method of creating an analog voltage by toggling a digital pin on and off.

The GPIOs map to the Hardware PWM peripherals as such:

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;margin:0px auto;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:3px 30px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-c3ow{border-color:inherit;text-align:center;vertical-align:top}
.tg .tg-0pky{border-color:inherit;text-align:center;vertical-align:top}
</style>
<table class="tg"><thead>
  <tr>
    <th class="tg-c3ow"></th>
    <th class="tg-c3ow" colspan="2"><b>PWM0</b></th>
    <th class="tg-0pky" colspan="2"><b>PWM1</b></th>
    <th class="tg-0pky" colspan="3"><b>ECAP</b></th>
  </tr></thead>
<tbody>
  <tr>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"><b>A</b></td>
    <td class="tg-0pky"><b>B</b></td>
    <td class="tg-0pky"><b>A</b></td>
    <td class="tg-0pky"><b>B</b></td>
    <td class="tg-0pky"><b>0</b></td>
    <td class="tg-0pky"><b>1</b></td>
    <td class="tg-0pky"><b>2</b></td>
  </tr>
  <tr>
    <td class="tg-0pky">GPIO5</td>
    <td class="tg-0pky">X</td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-0pky">GPIO6</td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky">X</td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-0pky">GPIO12</td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky">X</td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky">X</td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-0pky">GPIO13</td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky">X</td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-0pky">GPIO14</td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky">X</td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-0pky">GPIO15</td>
    <td class="tg-0pky">X</td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-0pky">GPIO16</td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky">X</td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-0pky">GPIO17</td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky">X</td>
  </tr>
  <tr>
    <td class="tg-0pky">GPIO18</td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky">X</td>
  </tr>
  <tr>
    <td class="tg-0pky">GPIO20</td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky">X</td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-0pky">GPIO21</td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky">X</td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky">X</td>
    <td class="tg-0pky"></td>
  </tr>
</tbody></table>