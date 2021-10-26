## Adafruit VL53L1X Time of Flight Distance Sensor PCB

<a href="http://www.adafruit.com/products/3967"><img src="assets/3967.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit VL53L1X Time of Flight Distance Sensor. 

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/3967

### Description

The Adafruit VL53L1X Time of Flight Distance Sensor (also known as VL53L1CX) is a Time of Flight distance sensor that has a massive 4 meter range and LIDAR-like precision. The sensor contains a very tiny invisible laser source and a matching sensor. The VL53L1X can detect the "time of flight", or how long the light has taken to bounce back to the sensor.

Since it uses a very narrow light source, it is good for determining the distance of only the surface directly in front of it. Unlike sonars that bounce ultrasonic waves, the 'cone' of sensing is very narrow. Unlike IR distance sensors that try to measure the amount of light bounced, the VL53L1X is much more precise and doesn't have linearity problems or 'double imaging' where you can't tell if an object is very far or very close.

This is the 'next generation' of the VL53L0X ToF sensor and can handle about ~30 to 4000mm of range distance, with up to 50Hz update rate. If you need an even smaller/closer range, check out the VL6180X which can measure 5mm to 200mm and also contains a light sensor.

The sensor is small and easy to use in any robotics or interactive project. Since it needs 2.8V power and logic we put the little fellow on a breakout board with a regulator and level shifting. You can use it with any 3-5V power or logic microcontroller with no worries. Works great with the 3.3V logic level of a Feather or Raspberry Pi, or the 5V level of a Metro 328 or Arduino Uno, this breakout is ready to work with most common microcontrollers or SBCs. and since it speaks I2C, you can easily connect it up with two data wires plus power and ground.

As if that weren't enough, we've also added SparkFun qwiic compatible STEMMA QT connectors for the I2C bus so you don't even need to solder. Just wire up to your favorite micro with a plug-and-play cable to get ToF data ASAP. For a no-solder experience, just wire up to your favorite micro, like the STM32F405 Feather using a STEMMA QT adapter cable. The Stemma QT connectors also mean the VL53L1X can be used with our various associated accessories. QT Cable is not included, but we have a variety in the shop

Communicating to the sensor is done over I2C with an API written by ST, so it's not too hard to port it to your favorite microcontroller. We've written a wrapper library for Arduino so you can use it with any of your Arduino-compatible boards.

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional details.
