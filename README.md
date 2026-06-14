# ESP32 Touch Sensor Project

## Overview

This project demonstrates the use of the ESP32's built-in capacitive touch sensor to control an LED. The LED turns ON when the touch sensor is touched and turns OFF when it is not touched.

## Features

* Touch-based LED control
* Uses ESP32 built-in capacitive touch sensing
* No external push button required
* Real-time status monitoring through Serial Monitor

## Components Required

* ESP32 Development Board
* LED
* Touch Sensor
* Jumper Wires
* Breadboard

## Circuit Connections

| Component        | ESP32 Pin                       |
| ---------------- | ------------------------------- |
| Touch Sensor Pin | Touch GPIO Pin (GPIO4) |
| LED Anode (+)    | Digital Output Pin (GPIO13)     |
| LED Cathode (-)  | GND (through resistor)          |

## Working Principle

The ESP32 continuously reads the touch sensor value. When a touch is detected, the LED is switched ON and a message is displayed on the Serial Monitor. When no touch is detected, the LED is switched OFF.

### Serial Monitor Output

```text
Touched! LED ON
Not Touched! LED OFF
```

## Code

Upload the Arduino sketch to the ESP32 using the Arduino IDE and open the Serial Monitor to observe the touch status.

## Output

### LED OFF State

When the touch sensor is not touched:

* LED OFF
* Serial Monitor displays:

```text
Not Touched! LED OFF
```

### LED ON State

When the touch sensor is touched:

* LED ON
* Serial Monitor displays:

```text
Touched! LED ON
```

Output

https://github.com/PandrangiJahnavi/ESP32_Touch_Sensor_Project/blob/main/LED%20NO%20USING%20TOUCH%20SENOR.jpeg
https://github.com/PandrangiJahnavi/ESP32_Touch_Sensor_Project/blob/main/LED%20OFF%20USING%20TOUCH%20SENOR%20.jpeg
https://github.com/PandrangiJahnavi/ESP32_Touch_Sensor_Project/blob/main/TOUCH%20SENSOR%20OUTPUT.png


## Applications

* Smart Touch Switches
* Touch-Controlled Lighting


## Future Enhancements

* IoT monitoring using Wi-Fi
* Mobile app control
* Touch-based appliance control
* Data logging to cloud platforms

## Author

**Pandrangi Jahnavi**

Electronics and Communication Engineering (ECE) | IoT & Embedded Systems Enthusiast
