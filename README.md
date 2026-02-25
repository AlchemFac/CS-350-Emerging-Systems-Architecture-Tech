# CS-350 Emerging Systems Architecture & Technology

This repository contains coursework and project artifacts completed for CS-350.

## Course Overview
This course focuses on embedded systems, system architecture, hardware-software integration, and state machine design.

## Topics Covered
- Raspberry Pi configuration
- GPIO programming
- I2C communication
- UART communication
- Temperature and humidity sensor integration
- State machine implementation
- LCD display control
- Embedded system architecture documentation

**Thermostat Embedded System Project
Project Summary**

In this course, I developed an embedded thermostat system using a Raspberry Pi. The system reads temperature data from an I2C sensor, allows user input through GPIO buttons, controls LED indicators, updates a 16x2 LCD display, and sends status updates over a serial connection.

The project solved the problem of coordinating multiple hardware components through structured interface software. A finite state machine was used to manage the three operating modes: off, heat, and cool.

**What I Did Well**

I successfully implemented a working state machine that controlled hardware behavior based on temperature and user input. The system integrates sensor readings, button interrupts, LED control, display output, and UART communication into a single cohesive application.

The program is organized into logical sections, making it readable and easy to follow.

**Areas for Improvement**

The system could be improved by adding stronger error handling for sensor or communication failures. I could also improve abstraction to make testing easier without relying on physical hardware.

**Tools and Resources Added**

Through this project, I gained experience working with:

- Raspberry Pi hardware

- GPIO input and PWM output

- I2C communication

- UART serial communication

- Finite state machine design in Python

**Transferable Skills**

This project strengthened my ability to:

- Design structured embedded systems

- Integrate hardware with software

- Manage state-based logic

- Write modular and maintainable Python code

These skills are applicable to embedded systems, IoT applications, and hardware-integrated software development.

**Maintainability and Readability**

The project is organized using classes and clearly defined methods. Hardware control, state transitions, and display updates are separated logically, making the system adaptable for future enhancements.

## Author
Juan Navarro
Southern New Hampshire University
