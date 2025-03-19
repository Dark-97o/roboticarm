# Robotic Arm Project

## Overview
The Robotic Arm project is designed to control a robotic arm using servos and Bluetooth communication. It allows users to manipulate the arm's movements through commands sent via Bluetooth.

## Features
- Control up to 6 servos for precise movement
- Bluetooth connectivity for remote operation
- Ability to save and run predefined movements

## Installation
1. Ensure you have the required libraries:
   - `Servo`
   - `SoftwareSerial`
2. Connect the servos to the appropriate PWM pins on the Arduino board.

## Usage
- Commands can be sent via Bluetooth to control the arm:
  - "s1 [position]" to move servo 1 to a specific position
  - "SAVE" to save the current positions of the servos
  - "RUN" to execute the saved movements
  - "RESET" to clear saved positions

## Authors
- Subhranil Baul

## License
This project is licensed under the MIT License.
