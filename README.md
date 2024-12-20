# PBasic-Programming
This repository contains solutions to four PBasic programming challenges focusing on input handling, coordinate system visualization, game development, and real-time counting systems.

## Problem 1: Two-Number Comparison

 Write and implement a PBasic program to do the following. Using the debugin command, have a user enter  two  integers  (Num1  and  Num2)  in  the  range  of  -127  to  127.  Accept  and  store  the  input  in  two  Byte-sized  variables and display the entered numbers with correct numerical value and sign. Next, your PBasic program should correctly   establish   and   indicate   the   ordering   of   Num1   and   Num2,   i.e.,   Num1>Num2,   Num1<Num2,   or   Num1=Num2. 

## Problem 2: Coordinate System Display
Using  the  debug  command,  graphically  display  the  following  coordinate  system  within  the  debug  terminal.      

         3|            
         2|            
         1|    
    ------+------ <br/>
    -3-2-1| 1 2 3    
        -2|           
        -3|       
  Now,  write  a  program  that  does  appropriate  scaling  and  offset  to  display  an  asterisk  at  a  user-dictated  (x,y)  coordinate (e.g., (2,2) or (1,3)). Note the extra space between characters on the positive side of the horizontal axis
## Problem 3: Cold and Hot Game

Cold and Hot Game A player guesses a number between 0 and 99. Each time the player enters a guess; s/he  will  get  feedback  in  the  form  of  cold  (too  low),  hot  (too  high),  or  win  (correct  guess).  Three  LEDs  and  two  buttons  will  be  used.  The  LEDs  stand  for  the  feedback  (one  for  cold,  one  for  win,  and  one  for  hot).  User input between 0 and 99 can be selected using two buttons B1 and B2. The button B2 is used to input the tens digit and the button B1 is used to input the ones digit. Thus, e.g., by pressing B1 three times and B2 two times, the user enters the number 23. The user guesses and the feedback must be displayed on the debug window. The player has three chances to guess the correct answer. When the game is over, blink all the LE

### Components
- LED 1: Cold indicator (too low)
- LED 2: Win indicator (correct)
- LED 3: Hot indicator (too high)
- Button B1: Ones digit input
- Button B2: Tens digit input

### Game Flow
1. User inputs number using B1 and B2
2. System provides feedback via LEDs
3. Game continues for max 3 guesses
4. All LEDs blink when game ends

## Problem 4: Pupil Counting System

### Description
Individuals will enter and exit the school from two separate gates. A pressure-sensitive pad at the entrance gate will register  entrance  by  an  individual  whenever  it  is  depressed.  Another  pressure  sensitive  pad  at  the  exit  gate  will  register exit by an individual whenever it is depressed. A microcontroller will continuously monitor the two pressure pads. You are to develop a prototype real-time pupil counting system. Use two buttons to mimic the pressure pads and  write  a  program  that  will  provide  real-time  people  count.

### Components
- Two buttons simulating pressure pads:
  - Entry gate button
  - Exit gate button
- Real-time count display

### Features
1. Continuous monitoring of entry/exit points
2. Real-time count updates
3. Display of current occupancy

## Problem 5: Potentiometer Voltage Measurement

### Objective
Compare voltage measurements from a potentiometer using both ADC and direct interfacing methods.

### Components Required
- Basic Stamp 2 microcontroller
- Potentiometer (10kΩ recommended)
- Analog to Digital Converter
- Connecting wires

## Problem 6: LED Transistor Control

### Description
Two-part exercise implementing transistor-based LED control:
1. Digital control via BS2 pin
2. Analog control via potentiometer

### Requirements
Part 1:
- Interface LED with NPN transistor (2N3904)
- Control LED state using BS2 pin P0
- Implement appropriate resistor values

Part 2:
- Replace BS2 control with potentiometer
- Connect potentiometer between Vdd and Vss
- Document LED behavior changes

## Problem 7: Angular Position Sensor

### Description
Create an angular position measurement system using two methods:
1. Potentiometer in RC circuit
2. Potentiometer in 555-timer circuit

### Requirements
- Mount potentiometer on calibrated display (0-360°)
- Create dial indicator system
- Implement BS2 program using RCTime command
- Calibrate for accurate angle reporting
- Select appropriate C and R2 values for both methods

## Problem 8: 555 Timer LED Control

### Description
Implement controllable LED blinking using 555 timer circuit with potentiometer adjustment.

### Requirements
- Control LED blinking via BS2 pin P1
- Measure blinking cycle durations using PULSIN
- Calculate and display blinking frequency
- Document theoretical timing when pot = 0Ω

### Expected Measurements
- LED ON duration
- LED OFF duration
- Blinking frequency
- Theoretical timing calculations


