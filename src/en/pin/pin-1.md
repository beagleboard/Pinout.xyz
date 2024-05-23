BeagleY-AI generates it's 3v3 rail (named VDD_IO_3V3) from the TPS65219 PMIC Buck 1 regulator. This results in a max system power consumption of 3.5A on the 3.3V rail.
Since the 3v3 IO rail is used by a lot of system components, such as the ethernet PHY, USB hub, HDMI framer etc, it is recommended that you do not exceed 500mA of current draw from the 3v3 regulator. 

You should generally use the 5V supply, coupled with an external 3v3 regulator for 3.3v projects.