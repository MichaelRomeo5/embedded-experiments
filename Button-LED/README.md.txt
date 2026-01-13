## Button-Controlled LED

**Objective:**  
Control an LED using a push button as a digital input.

**Hardware Used:**
- Raspberry Pi Pico
- Push button
- LED
- Resistors
- Breadboard

**Software:**
- MicroPython

**Concepts Covered:**
- GPIO input configuration
- Internal pull-up resistors
- Active-low logic
- Conditional control

**Description:**
The button is configured with an internal pull-up resistor. When the button is pressed, the input reads low (0), causing the LED on GPIO pin 22 to turn on.

**What I Learned:**
- How to read digital inputs
- How pull-up resistors work
- How to handle active-low signals in code
