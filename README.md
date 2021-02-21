# Air_Quality_Monitoring
An IoT-based Air Quality Monitoring System constructed with the Arduino language, the ESP8266 Node 12-E  Microcontroller, &amp; the PMS5003 PM2.5 air particle and dust laser sensor by Plantower. Was used to create a geo-map visualization of collected particulate matter air-quality data of the UTA campus. 

Using the connected air quality sensor and MCU, data that reflected the PM1.0 (particulate matter with a diameter of 1.0 cubic micrometers or less), PM2.5, and PM10 air quality of certain locations within and around the UTA campus was collected. Data gathered, by two undergraduates and myself, was then pooled together in CombinedFeed.xlsx and uploaded to the cloud (MathWork’s ThingSpeak cloud service) with the Arduino IDE. With ThingSpeak, Microsoft Excel, EasyMapMaker.com, and Google Maps an air-quality heat map was created for data visualization. 

This project was created under the supervision of Dr. Ming Li for OurCS@DFW, an undergraduate group research competition. Without my teammates' presence, I presented a PowerPoint of my team's findings and project technicalities to the public and to a panel of judges at UTA’s 1st annual Student Computing Research Festival (SCRF). 

This system requires the Arduino core for ESP8266 WiFi chip to be installed. The Arduino core for ESP8266 WiFi chip is found at https://github.com/esp8266/Arduino.

<img src="https://github.com/Angelica-M/Air_Quality_Monitoring/blob/main/HeatMap.JPG" width=800><br>
Heat map was created with EasyMapMaker.com (https://www.easymapmaker.com/) using the contents of CombinedFeed.xlsx as input.

### License and credits ###
Copyright [2021] [Ming Li, Srinivasan Murali, Huadi Zhu, Angelica Magnussen, Dongqing (Grace) Ye, Ashlei Burrola]

# Arduino on ESP8266

The Arduino core for ESP8266 WiFi chip lets you write sketches, using familiar Arduino functions and libraries, and run them directly on ESP8266, with no external microcontroller required. ESP8266 Arduino core comes with libraries to communicate over WiFi using TCP and UDP, set up HTTP, mDNS, SSDP, and DNS servers, do OTA updates, use a file system in flash memory, and work with SD cards, servos, SPI and I2C peripherals.

- [Latest release documentation](https://arduino-esp8266.readthedocs.io/en/2.6.3/)
- [Current "git version" documentation](https://arduino-esp8266.readthedocs.io/en/latest/)
- [Install git version](https://arduino-esp8266.readthedocs.io/en/latest/installing.html#using-git-version) ([sources](doc/installing.rst#using-git-version))

Documentation: [https://arduino-esp8266.readthedocs.io/en/2.6.3/](https://arduino-esp8266.readthedocs.io/en/2.6.3/)

### License and credits ###

Arduino IDE is developed and maintained by the Arduino team. The IDE is licensed under GPL.

ESP8266 core includes an xtensa gcc toolchain, which is also under GPL.

Esptool.py was initially created by Fredrik Ahlberg (@themadinventor, @kongo), and is currently maintained by Angus Gratton (@projectgus) under GPL 2.0 license.

Espressif SDK included in this build is under Espressif MIT License.

ESP8266 core files are licensed under LGPL.
