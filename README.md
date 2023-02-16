# Food-Spoilage-Detection
This project uses an Arduino board with a methane sensor to detect levels of methane and determine whether food has spoiled or not. The code sends data to a NodeMCU, which can be used to alert the user through an external device.

## Getting Started
To get started with this project, you will need the following:

Arduino Board

A methane sensor

A NodeMCU

A breadboard and jumper wires

An LED (green and red)

A buzzer

## Installing

Connect the methane sensor to the analog pin A5 on the Arduino board.

Connect the green and red LEDs to digital pins 11 and 12, respectively.

Connect the buzzer to digital pin 10.

Connect the NodeMCU to the Arduino board using jumper wires.

## Usage
Upload the code to the Arduino board.

Open the serial monitor in the Arduino IDE to view the methane range and data being sent to the NodeMCU.

Use the NodeMCU to alert the user when food has spoiled.
