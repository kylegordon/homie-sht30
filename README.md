[![Build Status](https://travis-ci.org/kylegordon/homie-sht30.svg?branch=master)](https://travis-ci.org/kylegordon/homie-sht30)

# homie-sht30

# DEPRECATED 
## In favour of [Tasmota](https://github.com/arendst/Sonoff-Tasmota)

A simple ESP8266 Arduino sketch that reads the temperature from a lone SHT30 sensor, and publishes it to an MQTT broker.

Uses the [Homie](https://github.com/marvinroger/homie-esp8266/releases) framework, so you don't need to worry about wireless connectivity, wireless configuration persistence, and all that. Simply compile and upload, and configure using the Homie configuration tool.
All future flashes will not overwrite the wireless configuration.

Best used with PlatformIO. Simply git clone, edit ROM IDs as appropriate, pio run -t upload, watch the dependencies download and compile, and then if required do the initial Homie configuration with the tool for Homie 2 at http://setup.homie-esp8266.marvinroger.fr/
