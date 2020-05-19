# PCF857x for Sming

**This project is archived now**

I am no longer maintaining it.

Basically all [WereCatf](https://github.com/WereCatf/PCF8574_ESP) and [Rob Tillaart](http://playground.arduino.cc/Main/PCF8574Class) work, stripped of things not related to ESP8266 and adapted to [Sming](https://github.com/SmingHub/Sming) framework.

For documentation see original sources, nothing has changed in library interface.

## Why bother?

Sming already includes `I2CIO.h` used in LiquidCrystal library. This one has more features and adds support for PCF8575.
