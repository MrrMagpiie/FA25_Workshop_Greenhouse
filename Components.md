[Pages](Pages.md)

# Current Setup
Our current setup can be broken down into 4 categories
- Microcontroller
- Home-Assistant and ESP-home
- Sensors
- Hardware

## General Description
the current setup functions as follows:
the Sensors and Automation Components are wired into a Microcontroller that has Wi-fi capabilities (the ESP-32 s3) from there the Microcontroller reports back to the server hosting Home Assistant. the connection to, and programing of, the Microcontroller is handled through the ESP-home integration in Home-Assistant. the Home Assistant server processes the sensor information and reports back to the Microcontroller when and how to activate the Automation Components.

Example: currently there is a soil moisture sensor and a pump set up connected to the Microcontroller. The Microcontroller regularly reports to the Home Assistant server what the current soil hydration is. within Home Assistant I have programed an automation that states if the soil hydration drops below 30% then the relay controlling the Pump is set to turn on for 5 seconds, turn off again then wait another 10 minutes to check the soil hydration again.

## Microcontroller
The microcontroller we are using is a ESP32-S3 

## Software
### Home Assistant
The main software component of the automation process is the Home Assistant server.
The server handles the collection and aggregation of data as well as the control of the automation hardware
### ESP-Home
ESP-Home is a tool in home assistant used to interface between the home assistant server and a microcontroller with Wi-Fi capabilities as well as to program the microcontroller itself.   
## Sensors
we have an array of sensors setup the major components in the system include
- Air Temperature
- Water Temperature
- Water PH
- Water TDS
- Light Level

### Specific Sensors
| Type       | Sensor            |
| ---------- | ----------------- |
| Lux        | TSL2591           |
| Air Temp   | SHT30             |
| Water Temp | DS18B20           |
| TDS        | Arduino TDS Meter |
| PH         | PH4502C           |
| Humidity   | SHT30             |
## Hardware
We have a few pieces of hardware that will control the environment in the Growing area
- Ventilation fans
- Peristaltic Pumps (x4)
	- PH up
	- PH down
	- Nutrient A
	- Nutrient B
- Grow Lights