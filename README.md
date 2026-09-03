# SPAR

![SPAR](IMAGES/pcb6.png)

This is a flight controller primarily designed for fixed wing aircraft (or quadcopters etc) that is designed to 
run either BetaFlight, INAV or ArduPilot firmware. It handles flight stabilization, OSD, control of servos, waypoints,
data logging and anything else any other flight controller can do. This flight controller has an STM32H743 which is 
an extremely capable MCU with a blazing fast speed of up to 480MHz. Most likely overkill for the majority of applications
but it can accomodate for the most demanding projects. I made it as I was interested in the design of such systems
and also enjoy building aircraft and could find a highly capable flight controller useful plus the benefit that I have
built it myself.

Specs:

- ICM-42688-P for peak performance and high resolution positional sensing
- STM32H743 for processing whatever you need
- 5V and 9V buck converters for handling high power peripherals
- Micro SD card for black box logging
- 4 in 1 ESC support with DSHOT
- 6 other PWM outputs
- Analog OSD through AT7456E
- Support for external magnetometer, airspeed sensor and GPS
- BMP280 barometer for altitude measurements
