# Voltage signal conditioner

A simple yet functional printed circuit board (PCB) design for a voltage sensor and signal conditioner, primarily developed for voltage source inverter (VSI) applications. Both the schematic design (.sch) and board layout (.brd) were developed in EAGLE software.

Being specified for an 127 V RMS voltage, it accepts a maximum amplitude of 200 V. According to the schematic diagram, it contains a voltage divider at the input with a trimmer for fine adjustment, a Zener limiter to limit voltage arround 10 V, and an isolation amplifier ISO124 integrated circuit (IC) powered with two independent voltage sources. The output has a jumper allowing the selection of RC filtering on the signal.

<div align="center">
<img width="655" height="312" alt="voltage_conditioner" src="https://github.com/user-attachments/assets/0bf8f606-c722-4a85-8185-c2656deb57af"/>
</div>

##

The figures presented in the sequence show stages involved in manufacturing the PCB and its final destination on a panel for VSI control purposes.

<div align="center">
<img width="655" height="420" alt="voltage_conditioner" src="https://github.com/user-attachments/assets/8e567b95-009f-46de-9b9c-5109cd70feee" />
</div>
