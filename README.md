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

[Insert original circuit image here]

Modified Circuit

An LED was added to the original design to provide a visual response to the push button's input.

[Insert modified circuit image here]

3. Components

- Arduino board: [Model]
- Push button
- LED
- Resistors: [Values]
- Breadboard
- Jumper wires

4. How It Works

Pull-Down Resistor

A pull-down resistor ensures that the Arduino's digital input reads LOW when the push button is not pressed.

When the button is pressed, the input is connected to HIGH, allowing the Arduino to detect the change in state.

This prevents the input pin from being left floating and producing unreliable readings.

LED Output

The Arduino reads the button's state and uses it to control the LED.

[Explain the exact behaviour of your LED here.]

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