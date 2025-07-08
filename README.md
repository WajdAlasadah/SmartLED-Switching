# SmartLED-Switching
💡 Project Description
This is a simple project using Arduino to control three LEDs with three push buttons.
Each button controls one LED independently.
When the button is pressed, the LED turns on.
Pressing the same button again turns the LED off — and so on for each button.

This project is great for learning how to read button states using INPUT_PULLUP, and how to work with digital outputs to turn LEDs on and off.
It’s suitable for beginners or anyone who wants to understand basic light control using Arduino.

🧰 Components
Arduino board (e.g., Uno)

Three push buttons

Three LEDs

Three 470-ohm resistors (optional, but recommended for the LEDs)

Breadboard

Jumper wires

⚡ Wiring
Each button is connected between a digital pin and GND.
Since the code uses INPUT_PULLUP, no external resistor is needed for the buttons.

Each LED is connected so that the positive leg (anode) goes to a digital pin,
and the negative leg (cathode) goes to GND.
It is recommended to place a 470-ohm resistor in series with the positive leg.

🟢 How It Works
When a button is pressed, the corresponding LED turns on.
Pressing the same button again turns the LED off.
Each button works independently from the others.

