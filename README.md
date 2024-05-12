# MSP430x2xx-Embedded-C-State-Machine-Driven-LED-Control-and-Display

This project implements an embedded C program for the Texas Instruments MSP430x2xx microcontroller family using a finite state machine (FSM) architecture to control and display LEDs.

The FSM design allows for modularity and efficient handling of user input from four pushbuttons to execute different LED operations.

# Features
• State 1 (PB0): Displays a pre-defined student ID number on the LED array sequentially with a 0.5-second delay between digits (uninterruptible).

• State 2 (PB1): Sequentially illuminates LEDs from right to left with a 0.5-second delay for 7 seconds (uninterruptible).

• State 3 (PB2): Generates a high-resolution PWM signal at a specified frequency (kHz) and 75% duty cycle on a designated pin.

• State 4 (Idle): Turns off LEDs and enters sleep mode (interruptible).

# Conclusion 
This embedded C project demonstrates the successful implementation of a finite state machine (FSM) to control LED behavior on the MSP430x2xx microcontroller. It showcases user input handling, modular code structure, and basic PWM generation.
Feel free to explore the code, experiment with different functionalities, and consider potential extensions like additional button actions, more complex LED patterns, or communication with external sensors.
