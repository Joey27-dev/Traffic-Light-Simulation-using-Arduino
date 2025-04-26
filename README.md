**Traffic-Light-Simulation-using-Arduino**

**Description**
This project simulates a basic traffic light system using an Arduino board and three LEDs: Red, Yellow, and Green.The LEDs light up in sequence — green, yellow, then red — with realistic timing delays to mimic an actual traffic signal.

**Components Used**

- ESP-32
- 1 × Red LED
- 1 × Yellow LED
- 1 × Green LED
- 3 × 220Ω resistors
- Jumper wires
- Breadboard
  

**Circuit Connections**

- LED Color	Arduino Pin
- Red	Pin 5
- Yellow	Pin 4
- Green	Pin 2
(Note: Each LED was connected in series with a 220Ω resistor to prevent burning out the LEDs.


**Code Behavior**

Green LED turns ON for 5 seconds (Go 🚗).

Yellow LED turns ON for 2 seconds (Get ready ⚡).

Red LED turns ON for 5 seconds (Stop ✋).


**How it Works**

The setup() function sets each LED pin as an output.

The loop() function controls the sequence of lights:

Turns the green LED on, waits, then turns it off.

Immediately turns the yellow LED on, waits, then turns it off.

Immediately turns the red LED on, waits, then turns it off.


**How to Run**
- Connect your Arduino and LEDs according to the diagram above.
- Upload the provided code using the Arduino IDE.
- Watch your LEDs simulate a traffic light!
  

**Circuit Diagram**
