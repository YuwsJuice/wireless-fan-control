## Video: [https://youtu.be/k6CHJ9VKTnY](https://www.youtube.com/watch?v=UywTtftcw1k)

# Info
Project that controls electric fan wirelessly. has displays and temperature sensors. 

# Prerequisites:
Arduino IDE, but PlatformIO is better.
Link: https://www.arduino.cc/en/software

# Parts List
* ESP8266
* Perfboard
* wires
* SSD1306 OLED display
* Four-channel relay module
* Buttons
* DHT11
* DS18B20

# Libraries
Library Name         |       Link       | Description
:------------------- | ---------------------- | :------------------------------------------------
ESP8266WiFi          | https://github.com/esp8266/Arduino/blob/master/libraries/ESP8266WiFi/src/ESP8266WiFi.h   | esp8266 wifi 
ESPAsyncTCP          | https://github.com/me-no-dev/ESPAsyncTCP | asynchronous TCP communication 
ESPAsyncWebServer    | https://github.com/me-no-dev/ESPAsyncWebServer | set up an asynchronous web server that can handle HTTP requests
Wire                 | standard Arduino library | I2C communication
Adafruit_GFX         | https://github.com/adafruit/Adafruit-GFX-Library | graphics core library
Adafruit_SSD1306     | https://github.com/adafruit/Adafruit_SSD1306 | SSD1306 oled display
OneWire              | https://github.com/PaulStoffregen/OneWire | Interfacing with DS18B20 temperature sensor
DHT                  | https://github.com/adafruit/DHT-sensor-library | dht11 library
DallasTemperature    | https://github.com/milesburton/Arduino-Temperature-Control-Library | used with dht11 library

# Tutorial
1. Wire the parts required, if you have a clone esp8266 install the required drivers (usually it's a CH340 or CP2102). Once installed, select the appropriate COM port when working with the ESP8266 in the Arduino IDE or other programming environments.
2. Install the required libraries. Then copy the [code](https://github.com/YuwsJuice/wireless-fan-control/blob/main/fan.ino) into Arduino IDE.
3. Connect your esp8266 in the correct port and upload.




