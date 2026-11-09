Arduino LED Pull-Down Circuit

1. Project Overview

This project explores the use of a push button as a digital input on an Arduino board, using a pull-down resistor to maintain a stable input state.

The original circuit was extended by adding an LED, allowing the button's input state to control a visual output.

Main objectives:

- Understand digital inputs and outputs.
- Understand the purpose of a pull-down resistor.
- Explore the difference between pull-down and pull-up configurations.
- Modify an existing Arduino circuit by adding an LED.

2. Circuit Design

Original Circuit

The initial circuit was based on an Arduino Open Source reference design.

<img width="720" height="300" alt="image" src="https://github.com/user-attachments/assets/4a3c9e14-f02c-4a7c-b497-d1924a14177c" />


Modified Circuit

An LED was added to the original design to provide a visual response to the push button's input.

<img width="1196" height="765" alt="image" src="https://github.com/user-attachments/assets/3678fe03-7d2c-40d4-a1b5-bf69000e70d5" />


3. Components

- Arduino board: Arduino UNO R3
- Push button
- LED
- Resistors: 220 Ohms, 10K Ohms
- Breadboard
- Jumper wires

4. How It Works

Pull-Down Resistor

A pull-down resistor ensures that the Arduino's digital input reads LOW when the push button is not pressed.

When the button is pressed, the input is connected to HIGH, allowing the Arduino to detect the change in state.

This prevents the input pin from being left floating and producing unreliable readings.

LED Output

The Arduino reads the button's state and uses it to control the LED.

The LED then checks whether it is receiving a low or high input. If the signal is low then it stays off, and if the signal is high the LED stays on for the amount of time the signal stays high. 

5. Development and Modifications

The original circuit design and initial programming structure were obtained from Arduino Open Source resources.

The circuit was modified by adding an LED to provide a visual output.

The code was also adapted to incorporate this additional functionality, with AI-assisted guidance during the modification process.

This project served as an opportunity to practise circuit adaptation, basic Arduino programming, and digital input/output control.

6. What I Learned

- The purpose of pull-down resistors.
- The difference between pull-up and pull-down configurations.
- How Arduino reads digital inputs.
- How to control an LED using a digital output.
- How to adapt an existing circuit and program.

7. References and Acknowledgements

See "references/sources.md" (references/sources.md) for the original circuit and programming references.

AI tools were used as supplementary assistance when adapting the circuit and code.
