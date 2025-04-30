# LED Traffic Light Simulation

## Description

This Arduino sketch simulates a basic traffic light using three LEDs: red, yellow, and green. Each LED is connected to a digital pin on the Arduino board. The program controls the LEDs in a timed sequence that represents a real-world traffic signal system.

## Hardware Requirements

- Arduino Uno (or compatible board)
- 3 LEDs (Red, Yellow, Green)
- 3 Resistors (220Ω recommended)
- Breadboard and jumper wires

## Circuit Connections

| LED Color | Arduino Pin |
|-----------|-------------|
| Red       | D5          |
| Yellow    | D4          |
| Green     | D2          |

Each LED should be connected in series with a resistor.

## How to Use

1. Connect the LEDs and resistors to the Arduino as shown above.
2. Upload the provided `.ino` file to the Arduino board.
3. Power the board. The LEDs will light up in the following cycle:
   - Green for 5 seconds
   - Yellow for 2 seconds
   - Red for 5 seconds
4. The cycle repeats continuously.

## File

- `sketch_mar30a_led_robot.ino`: Arduino sketch for traffic light simulation

## Author

Joey27-dev
