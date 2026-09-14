# Sensor-Based-Automation-System-using-ARM7
ARM7 LPC2148-based automation system using IR sensing, DC motor, stepper motor, buzzer, and LED control.

## Overview

An ARM7-based automation system using the LPC2148 microcontroller to detect objects and perform automated mechanical operations. An IR sensor triggers the system, which controls a DC motor, stepper motor, buzzer, and LEDs through GPIO-based control logic.

## Objectives

- Detect objects using an IR sensor
- Control a DC motor for mechanical actuation
- Control a stepper motor for precise movement
- Provide buzzer and LED indications
- Implement sensor-based automation using ARM7

## Hardware

- LPC2148 ARM7 Evaluation Board
- IR Sensor
- DC Motor
- Stepper Motor
- Buzzer
- LEDs
- Power Supply

## Working

IR Sensor → LPC2148 → Buzzer & LEDs → DC Motor → Stepper Motor → Reset

When an object is detected, the LPC2148 activates the buzzer and LEDs, operates the DC motor, and rotates the stepper motor clockwise to perform the required mechanical action. The stepper motor then returns to its original position for the next cycle.

## Technologies Used

- ARM7 LPC2148
- Embedded C
- GPIO Control
- Sensor Interfacing
- DC Motor Control
- Stepper Motor Control

## Implementation

The system was implemented on an ARM7 LPC2148 evaluation board and demonstrated the integration of sensors, indicators, and motor control.

## Result

The system successfully demonstrates sensor-based detection, indication, motor actuation, and mechanism reset using the LPC2148 microcontroller.
