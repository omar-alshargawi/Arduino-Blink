💡 Arduino LED Control with Push Buttons

A hands-on introduction to digital I/O control – no prior experience needed!
✨ Key Features

    Control 3 LEDs independently using tactile buttons

    Learn essential electronics concepts: pull-down resistors, current limiting, and signal debouncing

    Perfect for beginners – builds fundamental skills for IoT and embedded systems

🛠️ Hardware Setup
What You’ll Need
Component	Purpose
Arduino Uno/Nano	The brain of your project
LEDs (Red, Green, Yellow)	Visual feedback indicators
Tactile push buttons	User input triggers
220Ω resistors	Protect LEDs from overcurrent
10kΩ resistors	Stabilize button inputs (pull-down)
Breadboard & jumper wires	For easy prototyping
Circuit Connections

    LEDs → Digital pins D3, D4, D5 (through 220Ω resistors) → GND

    Buttons → Digital pins D6, D7, D8 (with 10kΩ pull-down to GND) → +5V

(Tip: Use a multimeter to verify connections if something doesn’t work!)
🎯 Core Learning Objectives

By building this project, you’ll master:
✅ Digital input handling – How Arduino reads button states
✅ Output control – Turning LEDs on/off programmatically
✅ Circuit design fundamentals – Why resistors are crucial
✅ Troubleshooting skills – Diagnosing common hardware issues
🚀 Getting Started

    Assemble the circuit following the wiring guide

    Upload the provided sketch (check the src folder)

    Test each button – They should toggle their paired LED instantly

    Experiment further:

        Change LED colors or pin assignments

        Add delays for blink effects

        Try controlling multiple LEDs with one button

📚 Deepen Your Knowledge
Why This Matters

This project teaches the foundation of all interactive electronics:

    Input/Output relationships (the basis of IoT devices)

    Hardware-software integration (how code interacts with circuits)

    Prototyping best practices (organization, debugging, iteration)

Next-Level Challenges

    Replace delay-based debouncing with interrupts for faster response

    Add serial monitoring to log button presses

    Create a light sequence triggered by button combinations

📸 Visual Guide

![LEDs-light-off](https://github.com/user-attachments/assets/45c55389-c030-4515-8ab7-7f05479f0fc1)

![LEDs-light-on](https://github.com/user-attachments/assets/718eda01-87bd-494b-9a3b-2e8f2439dfb9)

🎥 Video Tutorial

https://github.com/user-attachments/assets/06d842e5-7fb3-4fea-9a4e-81e2afdb08fa

🌟 Creator Spotlight

[Omar Alshargawi]

🤖 AI Engineer | Machine Learning Specialist
