# Lab Project: Blinky-Buzzy Toy with LCD Screen

## Description
This project involves creating a toy using the **MSP430 Microcontroller** by utilizing the board's features: buttons, LEDs, a speaker, and an **LCD screen**. The toy generates sounds, controls the LEDs' brightness, displays information on the LCD screen, and implements a state machine to manage its different states. The state machine transitions are controlled via the four buttons on the expansion board (P2.0-3).

One of the functions used to transition the state machine was written in assembly language, as required by the project guidelines.

The project was originally outlined by Dr. Eric Freudenthal as part of the curriculum for CS 3320 Intro to Computer Architecture at The University of Texas at El Paso.

## Features
- Generates sounds through the speaker.
- Dynamically changes the LEDs' brightness (both bright and dim).
- Displays status information on the **LCD screen** (e.g., current state of the toy).
- Implements a state machine to manage the toy's states.
- Transitions between states using the four buttons on the MSP430 expansion board (P2.0-3).
- One state transition function was implemented in assembly language.

## Files
The project consists of several source files and a Makefile:

- `project/main.c`: The main source code that handles the state machine logic, interacts with peripherals like LEDs, buttons, and the LCD screen.
- `project/led.c`: Functions to control the LED brightness and the LED screen.
- `project/buzzer.c`: Functions to generate sounds through the speaker.


