🚗 Smart Parking System – Digital Logic Design
📌 Overview
The Smart Parking System is a digital logic-based solution designed to efficiently manage parking spaces by counting vehicles entering and exiting the parking area. The system automates the process using digital ICs, seven-segment displays, and sensors, providing real-time occupancy information.

This project was developed as part of our Digital Logic Design coursework to integrate theoretical knowledge with practical circuit implementation.

🎯 Objectives
Count the number of cars entering and exiting the parking lot.

Display the current number of cars on a 7-segment display.

Indicate when the parking lot is full using an LED warning system.

Control a DC motor to open/close the parking gate automatically.

🛠 Components & Modules
Circuit 1 – 4-bit Synchronous Counter
IC 74LS190 – 4-bit up/down counter with preset capability.

Key Features:

Counts up/down depending on control inputs.

Preset option to set initial count value.

Outputs binary count values for display.

Working Principle:

Push buttons control the count direction.

Binary output drives a 7-segment decoder to display the count.

Circuit 2 – 7-Segment Display Decoder
IC 74LS47 – BCD to 7-segment decoder.

Function: Converts binary values from the counter into human-readable numeric form on the display.

Features: Supports common anode configuration for multiple digits.

Circuit 3 – Flip-Flops & Logic Gates
Flip-Flop (D-Type) – Stores the count state and updates on each clock pulse.

Logic Gates (AND, OR, NOT, XOR) – Control the system flow based on sensor inputs.

Function:

Detects vehicle entry/exit using infrared sensors.

Generates pulses to trigger the counter increment/decrement.

⚙ How the System Works
Vehicle Detection

Infrared sensors detect when a car enters or exits the parking area.

Counting Mechanism

The entry sensor triggers the counter to increment the count.

The exit sensor triggers the counter to decrement the count.

Display Output

The counter output is converted to a 7-segment display format to show the current number of parked cars.

Full Parking Indicator

When the count reaches maximum capacity, an LED is activated, and the entry gate is closed.

🖥 Simulation & Implementation
Software Used: Proteus for circuit simulation.

Hardware Components: Breadboard, jumper wires, ICs, resistors, LEDs, infrared sensors, 7-segment displays, and a DC motor for the gate.

Final Touch: Added two IR sensors for automated detection – one for entry and one for exit – connected to the counter circuit for real-time updates.

📷 Project Media
Circuit Diagram

Prototype

👨‍💻 Team Members
Jana Hazem – GitHub Profile

Yousef Mohamed

Osama Mohamed

Youssef Mohamed

