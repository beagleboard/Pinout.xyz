SCL Raspberry Pi'deki I2C pinlerinden biri. [I2c hakkında detaylı bilgi](/pinout/i2c).

```python
require 'socpin'
HIGH = 1
LOW = 0
OUTPUT = 1
INPUT = 0
io = socpin::GPIO.new
io.pin_mode(9,OUTPUT)
io.digital_write(9,HIGH)
```