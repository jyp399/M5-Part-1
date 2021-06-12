# M5-Part-1
# Group 4
Repository by Group 4 for the M5 Challenge Part 1

Part 1 programs the M5 Atom Matrix to work as a bikelight and as a temperature sensor 

## Installation ##
User needs M5 Atom Matrix and Arduino IDE Environment. Instructions for installation found in https://www.arduino.cc/en/software and https://docs.m5stack.com/en/arduino/arduino_development M5 Atom needs to be connected to any port in the computer under the Tools section in Arduino. Upload the code and the M5 will update and display corresponding code

Libraries

M5 Atom version 0.0.2

## Brake Light ##
In this mode, the M5 Atom Matrix is programmed to be a brake light. It contains 4 modes: OFF, Manual Red, Manual White, Automatic Red, Automatic White.

OFF: Black display

Manual Red: M5 blinks in red at constant interval

Manual White: M5 blinks in white at constant interval

Automatic Red: M5 detects acceleration changes and blinks in red in corresponding action

Automatic White: M5 detecs acceleration changes and blinks in white in corresponding action

When changing modes from automatic red or automatic white, LEDs must be in solid state (not in blinking state) for the mode to change

## Temperature ##
In this mode, the M5 Atom Matrix is programmed to be a thermometer. The M5 Atom Matrix records the temperature at a fixed interval. Tilting the M5 device will change the modes and display the corresponding temperature for that mode. 

Modes:

1: Active temperature and corresponding unit

2: Average temperature of last 24 hours and corresponding unit

3: Scale of temperature 

4: Graph

5: Change from Celsius to Fahrenheit

To return to the main menu, the M5 Atom has to be put facing down for 10 seconds

## Credits ##
Program developed by NYU Abu Dhabi students Juno Yoon Park (jyp399@nyu.edu), Aryamaan Dholakia (amd1139@nyu.edu), Shaheer Haider (sh5014@nyu.edu), and Mariam Aldhaheri (maa9345@nyu.edu) for the Design and Innovation Course (superLab(2021).remote)
