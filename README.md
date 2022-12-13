# PortableWeatherStation

Portable weather station using an M5Station-bat connected to an I2C device string.
Devices currently used are:

+ An I2C to Serial bridge with a GPS hooked up to the serial interface (DFRobot Interface)
+ An M5Stack ENV III (SHT30+QMP6988)
+ 32K Fram module
+ M5Stack Lux sensor (BH1750)
+ M5Stack eCO2/TVOC sensor (SGP30)

Depends on: 
+ https://github.com/wicked-rainman/ESP32Dispatcher.git
+  https://github.com/DFRobot/DFRobot_IICSerial.git
+  https://github.com/adafruit/Adafruit_NeoPixel.git
+  https://github.com/adafruit/Adafruit_SGP30.git
+  https://github.com/m5stack/M5Unit-ENV.git
+  https://github.com/claws/BH1750.git
+  https://github.com/RobTillaart/FRAM_I2C.git

