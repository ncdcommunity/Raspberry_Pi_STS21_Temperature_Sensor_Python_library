[![ STS21](STS21_I2C.png)](https://store.ncd.io/product/sts21-high-accuracy-temperature-sensor-%C2%B10-2c-i2c-mini-module/).

#  STS21

The STS21 from Sensirion offers a low-cost high-resolution temperature measurement with outstanding specifications over a wide temperature range.
This Device is available from www.ncd.io 

[SKU: STS21]

(https://store.ncd.io/product/sts21-high-accuracy-temperature-sensor-%C2%B10-2c-i2c-mini-module/)
This Sample code can be used with Raspberry Pi.

Hardware needed to interface STS21 temperature sensor With Raspberry Pi :
1. <a href="https://store.ncd.io/product/sts21-high-accuracy-temperature-sensor-%C2%B10-2c-i2c-mini-module/">STS21 temperature sensor</a>
2.  <a href="https://store.ncd.io/product/i2c-shield-for-raspberry-pi-3-pi2-with-outward-facing-i2c-port-terminates-over-hdmi-port/">Raspberry Pi I2C Shield</a>
3. <a href="https://store.ncd.io/product/i%C2%B2c-cable/">I2C Cable</a>

## Python
Download and install smbus library on Raspberry pi. Steps to install smbus are provided at:

https://pypi.python.org/pypi/smbus-cffi/0.5.1

Download (or git pull) the code in pi. Run the program.

```cpp
$> python STS21.py
```
The lib is a sample library, you will need to calibrate the sensor according to your application requirement.
