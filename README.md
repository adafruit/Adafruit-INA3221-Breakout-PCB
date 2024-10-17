## Adafruit INA3221 - Triple 0-26 VDC, ±3.2 Amp Power Monitor - STEMMA QT / Qwiic PCB

<a href="http://www.adafruit.com/products/6062"><img src="assets/6062.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit INA3221 - Triple 0-26 VDC, ±3.2 Amp Power Monitor - STEMMA QT / Qwiic. 

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/6062

### Description

This breakout board will solve all your multi-rail power-monitoring problems. Instead of struggling with up to 6 multimeters, you can just use the handy INA3221 chip on this breakout to both measure both the high side voltage and DC current draw of up to three power supplies over I2C with ±1% precision.

Most current-measuring devices such as our current panel meter are only good for low side measuring. That means that unless you want to get a battery involved, you have to stick the measurement resistor between the target ground and true ground. This can cause problems with circuits since electronics tend to not like it when the ground references change and move with varying current draw. This chip is much smarter - it can handle high or low side current measuring, up to +26VDC, even though it is powered with 3 or 5V. It will also report back that high side voltage, which is great for tracking battery life or solar panels.

A precision amplifier measures the voltage across the built-in 0.05 ohm, 1% sense resistors. Since the amplifier maximum input difference is ±163.8mV this means it can measure up to ±3.2 Amps. With the internal 13 bit ADC, the resolution at ±3.2A range is 0.4mA. Advanced hackers can remove the 0.05 ohm current sense resistor and replace it with their own to change the range (say a 0.01 ohm to measure up 16.4 Amps with a resolution of 2mA)

Usage is simple. Power the sensor itself with 3 to 5VDC and connect the two I2C pins up to your microcontroller - the logic level will be the same as the Vin power level. Then connect your target power supplies to VIN1/2/3+ and the loads to ground to VIN1/2/3-. If you want, set up over-current alerts on the warning or critical IRQ pins. We have libraries in both Arduino and CircuitPython/Python so you can use it with boards as simple as Arduino-compatible ATmegas all the way up to the latest Raspberry Pi's.

You don't even need to solder the I2C and power lines: we pre-attach 3.5mm terminal blocks and added SparkFun qwiic compatible STEMMA QT connectors for the I2C bus. Just wire up to your favorite micro using a STEMMA QT adapter cable. The Stemma QT connectors also mean the INA3221 can be used with our various associated accessories. QT Cable is not included, but we have a variety in the shop. If you need access to all of the pins, we include 0.1" pin header (so you can easily attach this sensor to a breadboard).

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional details.
