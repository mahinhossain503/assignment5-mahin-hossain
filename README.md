# assignment5-template
Basics of programming assignment 5

## Student

Fill here:

- Name Mahin Hossain
- Group B

## Description of the project
assignment 5.2

## User instruction
This file is a MicroPython program for a two-motor robot car. It sets up the motor pins and PWM speed controls, then defines functions to drive forward or backward by a distance and pivot left or right by an angle. Movement distances and turn angles are estimated from timed motor runs, using calibration values of 2 seconds per meter and 0.8 seconds per 90° turn at 50% speed.

When run, the program waits five seconds, then follows an S-shaped route: drive forward 0.5 m, turn left 90°, drive 0.5 m, turn left 90°, drive 0.5 m, turn right 90°, drive 0.5 m, turn right 90°, drive 0.5 m, turn around, and reverse 0.5 m. The motors are stopped briefly after each movement.
