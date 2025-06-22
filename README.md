# FPGA-Based Escape Room System using Quartus Prime

This project implements a complete digital Escape Room system on the DE1 FPGA board (Cyclone V) using Intel Quartus Prime 20.1. It was developed as part of the Industrial Electronics course, showcasing advanced knowledge of digital logic design, sequential circuits, and embedded systems prototyping.

Developed to simulate a real-world challenge through logic puzzles, this project integrates multiple digital modules, making it an engaging and technically solid experience.

Project Goals
- Understand and simulate edge-triggered JK flip-flops(based on 7476 IC).
- Design and implement module-7 up/down counters.
- Apply sequential logic to create challenge-based control systems.
- Integrate subsystems into a multi-stage Escape Room puzzle.
- Compile, simulate, and deploy the design on a real FPGA platform.

Tools & Technologies

- Quartus Prime 20.1(schematic/BDF design & waveform simulation)
- DE1 Terasic FPGA Board(Cyclone V – 5CSEMA5F31C6)
- Simulation via `.vwf` files and real hardware deployment

System Overview

The system is structured as a series of logic-based challenges that simulate an Escape Room. Users must solve each challenge through switches, buttons, and logic sequences to activate the final exit mechanism(light + door).

Modules

1. Output Module  
   Controls the final activation of the door and light system.

2. Math Challenge 
   Logic input & verification module based on mathematical puzzles.

3. Coded Message 
   Converts Gray code to binary and compares the entered code.

4. Sequence Logic Challenge  
   Uses FSMs and user input to validate a sequence of even or odd numbers.

5. 3-bit Comparator 
   Compares a user-entered binary word with the correct solution.

Quartus cannot be simulated on Github so a ZIP file is added in order that everybody would see the schematics in their quartus app and run all the simulations needed.
Hope you all enjoy the project.
