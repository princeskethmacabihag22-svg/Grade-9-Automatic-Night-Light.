Grade9-Automatic-Night-Light

Project Description

The Automatic Night Light is an Arduino-based system that automatically turns on an LED when the surroundings become dark.
It uses a light sensor to detect the amount of light in the environment. 

Input

The input is provided by a photoresistor or LDR (Light-Dependent Resistor). It measures the brightness of the surroundings

Process

The Arduino reads the value from the LDR. If the light level is below the set threshold, the Arduino determines that the
environment is dark and sends a signal to turn on the LED. If the environment is bright, the LED remains off.

Output

The output is an LED. The LED turns on when it is dark. The LED turns off when there is enough light.

Components Used

Arduino Uno
LDR or photoresistor
LED
220 Ω resistor
Jumper Wires

How the System Works
When the LDR detects bright surroundings, the Arduino keeps the LED turned off. When the surroundings become dark, the LDR reading changes. The Arduino detects this change and turns the LED on automatically.

PROJECT FILES
sketch.ino - Modified Arduino Program
app.py - Modified Streamlit Dashboard
requirements.txt - Required Python Libraries
README.md - Project Description

Wokwi Simulation
https://wokwi.com/projects/479263845338107905
