# Voltage difference detector

A printed circuit board (PCB) design for a voltage difference detector between two input voltages, originally developed for voltage source inverters (VSIs) paralleling applications. Both the schematic design (.sch) and board layout (.brd) were developed in EAGLE software.

Being specified for two 127 V sinusoidal inputs, it contains a circuit with a differential amplifier and a comparator. It calculates the instantaneous voltage difference between the inputs, which is proportional to both phase shift and amplitude of the signals, and compares it with an adjustable threshold. If the threshold is exceeded, the comparator activates a relay and a transistor that retains its current state until a reset button is pressed.

<div align="center">
<img width="413" height="514" alt="voltage_difference_detector" src="https://github.com/user-attachments/assets/6f65d31b-9646-4952-a55d-a5cdb4b28b5c" />
</div>

##

The figures presented in the sequence show stages involved in manufacturing the PCB and its final destination on a panel for VSI control purposes.
