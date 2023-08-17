# Multi Sensor 1

## Overview
Reliable smart home multi sensor utilizing zigbee2mqtt as a backend for fully local privacy first home automation. Combining Brightness Level, Temperature Measurement, Humidity Level, PIR Motion Detection, mmWave Motion Detection, and Bluetooth Low Energy presence detection into one multi sensor which has no need for wifi after setup with a zigbee2mqtt server and mqtt broker. Directly powered for 24/7 uninterrupted operation either via usb, mains power, or power over Ethernet. 

# Zigbee boards which can act as routers as well as switches
- CC2530
- CC2530 + CC2590
- CC2530 + CC2591
- CC2530 + CC2592 


## Versions
- v0.1: USB powered. Wifi + Bluetooth 
	- Initial Prototype
- v1: Usb powered. Zigbee + Wifi + Bluetooth. 
	- Designed for desktop or countertop use. 
	- Add cc2530 Zigbee Radio
	- Mount inside generic case.
- v: POE-P Powered. Zigbee + Bluetooth.
	- Designed to be installed at the end of the Ethernet cable and have a geometry ideal for adjusting detection cone. 
	- Add LM2596HV module for power over Ethernet and data transfer. 
	- Mount inside case with adjustable positioning 
- v3: Mains Powered. Zigbee + Wifi + Bluetooth.
	- Designed to be installed in a wall outlet replacing a light switch. 
	- Add HLK-PM01 mains power adapter
	- Built around standard light switch for install in wall. 