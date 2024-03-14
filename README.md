This code works best with the NodeMCU V2 ESP8266 module and an 0.96" OLED display
## Install and configure Arduino IDE

Make sure you use a version of the Arduino IDE which is supported by the ESP8266 platform. Follow the [tutorial on our documentation platform](https://docs.thingpulse.com/how-tos/Arduino-IDE-for-ESP8266/).

## Install libraries in Arduino IDE

Install the following libraries with your Arduino Library Manager in `Sketch` > `Include Library` > `Manage Libraries...`
* ESP8266 Weather Station
* JSON Streaming Parser by Daniel Eichhorn
* ESP8266 OLED Driver for SSD1306 display by Daniel Eichhorn. **Use Version 3.0.0 or higher!**

## Prepare the software
* [Create an API Key](https://docs.thingpulse.com/how-tos/openweathermap-key/) for OpenWeatherMap
* In the Arduino IDE go to `File` > `Examples` > `ESP8266 Weather Station` > `Weather Station Demo`
* Enter the OpenWeatherMap API Key
* Enter your WiFi credentials
* Adjust the location according to OpenWeatherMap API, e.g. Zurich, CH
* Adjust UTC offset

## Setup for PlatformIO

If you are using the PlatformIO environment for building

* choose one of the available IDE integration or the Atom based IDE
* install libraries 561, 562 and 563 with "platformio lib install"
* adapt the [WeatherStationDemo.ino](examples/WeatherStationDemo/WeatherStationDemo.ino) file to your needs (see details above)

## Why Weather Station as a library?
Because I realized that more and more the Weather Station was becoming a general framework for displaying data over WiFi to one of these pretty displays. But everyone would have different ways or sources for data and having the important part of the library would rather be the classes which fetch the data then the main class.
