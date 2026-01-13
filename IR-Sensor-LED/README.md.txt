## IR Sensor LED Control

**Objective:**  
Turn an LED on when an object is detected using an IR sensor module.

**Hardware Used:**
- Raspberry Pi Pico
- IR sensor module
- LED
- Breadboard

**Software:**
- MicroPython

**Concepts Covered:**
- Digital sensor interfacing
- Active-low signal behavior
- GPIO input reading
- Basic sensor debugging

**Description:**
The IR sensor provides a digital output that goes low when an object is detected. The microcontroller reads this signal and turns on an LED connected to GPIO pin 22.

**What I Learned:**
- How IR sensors output digital signals
- Differences between button inputs and sensor inputs
- How sensor range and alignment affect detection
