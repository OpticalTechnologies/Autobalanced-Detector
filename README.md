# Autobalanced-Detector
Full KiCAD design and production files of a self designed autobalanced detector for SRS microscopy. 

The autobalanced detector consists of three parts: 
1. Two of the same detector (SRSDetV5_24V) to detector the signal and reference beam.
2. The autobalancer module.
3. The PID, which is designed as a seperate PCB controlled by an MCU. The MCU also controlls logic circuitry on the autobalancer module.

The SRSDetV5 is optimized for use with a 20MHz modulation frequency and incorperates several filters to supress the repetition rate of a 40MHz pulsed laser and its harmonics. 

Firmware for the PID MCU and more information will follow.
