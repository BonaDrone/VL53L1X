This library derives from the 
Sparkfun [VL53L1X Arduino Library](https://github.com/sparkfun/SparkFun_VL53L1X_Arduino_Library), q.v. for details.
I have modified the Sparkfun library to work with my 
[CrossPlatformI2C](https://github.com/simondlevy/CrossPlatformI2C) library, the goal of which is to support
I<sup>2</sup>C devices like the VL53L1X on a variety of platforms (Arduino, RaspberryPi, NVIDIA Jetson).

So far I have tested the VL53L1X library on the following platforms:

* [Ladybug STM32L432](https://www.tindie.com/products/TleraCorp/ladybug-stm32l432-development-board/) development board
