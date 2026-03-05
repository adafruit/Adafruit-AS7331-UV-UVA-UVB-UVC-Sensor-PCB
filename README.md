## Adafruit AS7331 UV / UVA / UVB / UVC Sensor Breakout - STEMMA QT / Qwiic PCB

<a href="http://www.adafruit.com/products/6476"><img src="assets/6476.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit AS7331 UV / UVA / UVB / UVC Sensor Breakout - STEMMA QT / Qwiic. 

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/6476

### Description

The <b>Adafruit AS7331 UVA / UVB / UVC Sensor Breakout</b> is a perfect solution to UV sensing, no matter what 'type' you're sensing. Most UV sensors do just UVA, maybe ambient light too. But the AS7331 can read and differentiate between all the three bands. That means you can use it for human and agricultural UV alerts that tend to focus on  UVA and UVB as well as agricultural, germicidal, curing, and other UVC use cases. We particularly like that the three measurements are separated not just mixed together into one number.

The AS7331 has many gain and conversion settings configurable over I2C which means you can measure up to 349 mW/cm² on UVA channel, 386 mW/cm² on UVB and 169 mW/cm² on UVC at 1x gain, and with a responsivity as low as 2.38 nW/cm² per LSB.

In addition to the basic I2C connection, there's also the ability to change the default I2C address from 0x74 using the two jumpers on the back so you can have up to four sensors on the same bus. We also break out the READY pin that will let you know when a sensor conversion is complete, and the SYNC input, which can be used to synchronize the readings with an external pulse.

To make it easy to use, we mounted the tiny sensor on a STEMMA QT form factor breakout board, complete with level shifting circuitry and [SparkFun Qwiic](https://www.sparkfun.com/qwiic) compatible [Stemma QT](https://learn.adafruit.com/introducing-adafruit-stemma-qt) connectors. This means that you can, without needing to solder, connect our AS7331 breakout into your 3.3V or 5V microcontroller of choice be it an Arduino Uno, Raspberry Pi, or one of the many [CircuitPython-compatible boards](https://circuitpython.org/downloads).

Our Arduino and CircuitPython libraries make it easy to configure the AS7331 over I2C, with many included example sketches to help get you started. [QT Cable is not included, but we have a variety in the shop.](https://www.adafruit.com/?q=stemma+qt+cable&sort=BestMatch)

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional details.
