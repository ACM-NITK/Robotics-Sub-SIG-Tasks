# Robotics-Sub-SIG

# Robotics SIG Introductory Task

## Introduction
Hello Everyone!
This is the introductory task for our Robotics Sub Sig. Embedded Systems play a vital role in robotics. They control the various systems of the bot, they constitute the brain of your robot, having all your algorithms and intelligence at one spot. Hence it is important for roboticists, or wannabe robotists (please identify yourselves here ;)), to understand how to work with them.

## Lets Get Into It!
Most of you have heard and worked with the Arduino Uno. But as an engineer you need to work at optimising code and improving speed of execution, while lowering memory requirements. This is where Embedded C comes in. The following video series will give you an understanding of how to program your Arduino using AVR C:

[AVR C Tutorials](https://www.youtube.com/playlist?list=PLA6BB228B08B03EDD "Youtube Link for AVR C")
Average video size is around 15 mins. (Not your boring hour-long class videos)

## Questions
Please go through these  lectures and try to solve the following questions to be incorporated into the Robotics Sig:-

1. Design and code an Arduino Uno based circuit that reads input from a push button and sets an LED bulb’s value accordingly (LED is on if button is pushed and vice versa). This circuit also blink’s another LED at an interval of 1 sec. Both these tasks are to be run simultaneously and independently.\
    ___Hint:__ You may want to look up digital input and timer based interrupts in the video lectures._

2. Design and code an Arduino Uno based circuit that reads Analog Input from two potentiometers and controls an LED pin according to them.
    * Potentiometer 1’s input will decide if the LED gets switched on (Value> 3V switches the LED on, off otherwise)
    * Potentiometer 2’s input will control the brightness of the LED. \
    ___Hint:__ You will need to know how to read ADC input from the lectures, but two read two different inputs, you need to switch between two pins (find out which commands decide which pins are being read). You will need to understand PWM to put up analog value to an LED._

## Resources
You may use:

[TinkerCAD Circuits](https://www.tinkercad.com/learn/circuits "TinkerCAD circuits") for simulating your circuits.


This repository has source codes from the video lectures:- \
[Source Codes](https://www.dropbox.com/sh/7qdeb6n8rsm0li8/AABnZbQsrjMZbDJ1CB0jOrdXa "Source Codes") for simulating your circuits.


Submission Instructions:


* Make a branch with your name.
* Make a folder for each task in your branch.
* In each task, add your source code and a readme file.
* Put up links to the simulation video of your circuit along with a short description in the readme file.  
 

