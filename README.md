# Bio-Inspired Robotic Flower

An Arduino-based robotics project that mimics plant heliotropism - the natural ability of plants to orient themselves toward light sources.

## Project Overview

This system demonstrates bio-inspired robotics by recreating the natural behavior of flowers tracking the sun throughout the day. The robotic flower autonomously detects and follows light sources while responding to user proximity through interactive behaviors.

## Key Features

- **Autonomous Light Tracking**: Uses optical sensors to detect light direction and intensity, automatically orienting toward the brightest source
- **Multi-Axis Movement**: Coordinated servo motor control for smooth, natural-looking movements
- **Interactive Behavior**: Proximity detection triggers petal opening/closing animations, simulating plant responses to environmental stimuli
- **Modular Architecture**: Extensible hardware design based on Arduino platform, allowing easy modifications and upgrades

## Project Objectives

- Implement an automatic light source tracking mechanism using optical sensors
- Create a user interaction system through proximity detection
- Achieve coordinated control of multiple actuators (servo motors) to simulate natural movements
- Develop a modular and extensible hardware architecture based on the Arduino platform

## Technical Challenges

The project addresses several robotics challenges:

- **Light Direction Detection**: Using simple sensors to determine the direction and intensity of light in the environment
- **Sensory Information Processing**: Filtering, comparing, and interpreting sensor data to make correct orientation decisions while avoiding oscillations or erroneous movements
- **Mechanical Control**: Coordinating multiple actuators to rotate the structure toward the light source and simulate natural behaviors like petal opening and closing
- **Environmental Interaction**: Responding to both light sources and user presence, creating an interactive experience with complex, lifelike behavior

## The Problem Solved

In nature, many plants exhibit heliotropism - the ability to orient their vegetative organs (leaves, flowers) toward light sources to maximize photosynthesis. This evolutionary adaptation allows plants to optimize solar energy capture, essential for survival and growth.

Recreating this behavior in a robotic system requires solving several technical problems:

1. **Sensor Integration**: Unlike biological systems with complex photoreceptors, the artificial system uses simple sensors to detect light
2. **Real-time Decision Making**: Raw sensor data must be processed to make intelligent orientation decisions
3. **Smooth Motion Control**: Multiple servo motors must work in coordination to create natural-looking movements
4. **Interactive Response**: The system responds to environmental changes and user proximity in real-time

## Hardware Components

- Arduino microcontroller
- Light sensors (photoresistors/LDRs)
- Proximity sensor (ultrasonic/IR)
- Servo motors for multi-axis movement
- Adafruit PWM Servo Driver Library

## Applications

This project serves as a practical demonstration of bio-inspired robotics principles, integrating concepts from sensing, actuation, control systems, and embedded programming into a functional and visually engaging system.

## Documentation

Full project documentation is available in `Documentatie-Proiect.pdf`.

## Code Structure

The main implementation can be found in `Flora_Sensor_Servos.ino`, which includes:
- Sensor reading and processing
- Light tracking algorithm
- Servo motor control
- Proximity detection and interaction logic
