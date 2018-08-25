# 7 Stringed Midi Bass Guitar

## Overview
This repository showcases my 7 stringed MIDI bass guitar project that I have been working on for many years. The purpose of this repository is not to teach anyone how to make a MIDI bass or provide enough information for anyone to be able to copy my project, but simply to showcase my work in an accessible format.

### Background
I've ben playing bass guitar for over 25 years. In addition to my other instruments, I own 2 4 stringed MIDI bass guitars that I purchased almost 20 years ago and have always wanted similar functionality but more strings. My original idea was to create a 5 stringed MIDI bass guitar as I primarily play a 5 stringed bass. But after acquiring a Conklin 7 stringed bass I was infected with the "more is better" virus and couldn't stop myself from designing and creating a 7 stringed MIDI bass. So I purchased another 7 stringed bass to use in this project, leaving the original 7 stringed bass as a backup and non-MIDI practice bass. I started this project in 2003.

### Goal
My goal for this project is to have a working 7 stringed bass guitar with MIDI controller built in so that music played on the instrument with simultaneously transmit MIDI data to various other MIDI enabled equipment, such as sound modules, mixers, and lighting rigs. My inspiration for this project was my 4 stringed MIDI bases but they were created using old through-hole electronics and outdated microcontrollers and digital logic chips. Their circuit boards take up over half of the back of the guitar and the cavity used to store them creates an undesirable affect on the tonality of the bass when listening to the analog audio. My idea was to redesign new electronics that use surface mount electronic components, reducing the size of the circuit boards, and newer microcontrollers thus giving me more features at greater MIDI conversion speed.

### Steps
To complete this project the following steps are required:
1. Design the electronics
1. Have circuit boards manufactured
1. Order parts
1. Populate the circuit boards and test
1. Program the microcontrollers
1. Put it all together
1. 3D print a case for the final package
1. Mount the case to the guitar

### Progress
At this point I have created the electronics for the main circuitry and populated the 3 main boards. I have tested the basic functionality of the boards. I still have to create the "master" board that will be the final location of the microcontroller and the 3 MCP3008 8-channel 10-bit analog to digital converters. This has not been completed because the design has changed many times as newer, more capable microcontrollers have become available over the years. Originally I was using a PIC microcontroller, then a BasicX24, then 2 AVR ATMega2560's, and now I am exploring ARM microcontrollers. The modular circuit design allows me to change the microcontroller without changing any other aspect of the design.

So I am currently on the "programming the microcontroller" step in the process, although I have been here for a while and started this step over each time I upgrade to a different microcontroller.

### To Be Continued
I will be adding more to this document soon, such as an overview of the design and photos.
