# ESP-Watch 
An ESP  powered watch where you can customize the the ui as well  the case and all other thing and its usiing bare chip of ESP-S3 with pcb within antenna 

## Project Overview

ESP-Watch is a DIY smartwatch project featuring a custom-designed PCB, electronic components, and firmware.Its a hobby based poject as well as its a way of DIY thing i love to do hardwares 

## Features

- Custom PCB design
- Embedded firmware
- Weather information support
- Time synchronization using NTP
- 3D PCB design
- Hardware documentation

## Hardware Design

The hardware was designed using KiCad.

Project files:
- PCB layout
- Electrical schematic
- Gerber files
- Drill files

## Firmware

Firmware source files are available in the `Firmware/` directory.

Files:
- Basic.ino
- settings.h
- Basic.bin

## CAD Files

The `CAD/` directory contains STEP models for the project assembly and mechanical components.

## Bill of Materials

See [BOM.csv](BOM.csv) for the component list.

## PCB Manufacturing

Manufacturing files are provided:

- [Gerber Files](gerbers.zip)
- [Drill Files](drill%20files.zip)

## Repository Structure

ESP-Watch/
- CAD/
- PCB/
- Firmware/
- BOM.csv
- gerbers/
- drill files/

## Project Images
<img width="1920" height="1080" alt="Screenshot From 2026-11-20 15-36-06" src="https://github.com/user-attachments/assets/91f5d73d-44bf-4014-bb33-c2811767092f" />

<img width="1920" height="1080" alt="Screenshot From 2026-11-20 15-35-38" src="https://github.com/user-attachments/assets/0d03d25b-68ca-4dc8-bdfd-c3397ac0af05" />

<img width="1920" height="1080" alt="Screenshot From 2026-11-20 15-39-11" src="https://github.com/user-attachments/assets/4e672bfb-eae0-40c0-bf6a-468434f33363" />

<img width="1920" height="1080" alt="Screenshot From 2026-11-20 15-39-26" src="https://github.com/user-attachments/assets/39f9e05c-c70b-47a9-8192-9190f679dca3" />

## Fully-Assembled 
<img width="1920" height="1080" alt="Screenshot From 2026-11-20 15-40-39" src="https://github.com/user-attachments/assets/86f3c306-3897-4791-b6d7-3ddc47dbec79" />

##BOM


## Components
 
### ICs
 
| Designator | Qty | Part | Footprint |
|---|---|---|---|
| U4 | 1 | ESP32-S3 | QFN-56-1EP 7x7mm, 0.4mm pitch |
| U6 | 1 | BMA423 | LGA-12 2x2mm, 0.5mm pitch |
| U3 | 1 | TP4054 | SOT-23-5 |
| U2 | 1 | RT908033 | SOT-23-5 |
| U5 | 1 | USBLC6-2P6 | SOT-666 |
| U1 | 1 | SR2HARU | SR2HARU |
 
### Transistors and Diodes
 
| Designator | Qty | Part | Footprint |
|---|---|---|---|
| Q1 | 1 | CJ2301 | SOT-23 |
| Q2 | 1 | S8050 | SOT-23 |
| Q3 | 1 | AO3400A | SOT-23 |
| D1, D3, D4, D5 | 4 | MBR0530 | SOD-123 |
| D2 | 1 | 1N4001 | SOD-123F |
 
### Inductors
 
| Designator | Qty | Value | Footprint |
|---|---|---|---|
| L2 | 1 | 47 µH, 0.5 A |L_0402_1005Metric
| L1 | 1 |7.5nH  | 0402 | L_0402_1005Metric
 
### Crystals and Antenna
 
| Designator | Qty | Part | Footprint |
|---|---|---|---|
| Y1 | 1 | 32.768 kHz | Crystal SMD 2012, 2-pin |
| Y2 | 1 | 40 MHz | Crystal SMD 2520, 4-pin |
| AE1 | 1 | Chip antenna | SWRA117D |
 
### Connectors and Electromechanical
 
| Designator | Qty | Part | Footprint |
|---|---|---|---|
| J1 | 1 | Battery connector | 1.25T-2PWT (Molex 532610271) |
| J2 | 1 | Micro USB | USB Micro-B |
| J3 | 1 | FPC24 (0.5 mm) | 24-pin 0.5mm ZIF |
| M1 | 1 | Vibration motor | Motor header |
| SW1-SW4 | 4 | Buttons (BTN1-BTN4) | EVQPUC |
 
### Test Points
 
| Designator | Qty | Signal |
|---|---|---|
| TP1 | 1 | TX |
| TP2 | 1 | RX |
| TP3 | 1 | BOOT |
| TP4 | 1 | 3V3 |
| TP5 | 1 | GND |
| TP6 | 1 | SCL |
| TP7 | 1 | SDA |
 
### Resistors (0402)
 
| Designator | Qty | Value |
|---|---|---|
| R17 | 1 | 2.2 Ω |
| R13 | 1 | 1 kΩ |
| R1, R3, R18, R20 | 4 | 10 kΩ |
| R5, R14 | 2 | 51 kΩ |
| R2, R4, R6, R7, R8, R10, R11, R15, R19 | 9 | 100 kΩ |
| R9 | 1 | 360 kΩ |
| R16 | 1 | 1 MΩ |
| R12 | 1 | TBD |
 
### Capacitors
 
| Designator | Qty | Value | Footprint |
|---|---|---|---|
| C16, C19 | 2 | 22 pF | 0402 |
| C17, C18 | 2 | 18 pF | 0402 |
| C5, C6, C11, C12, C13, C14 | 6 | 100 nF | 0402 |
| C2, C3, C4, C15 | 4 | 1 µF | 0402 |
| C22-C29 | 8 | 1 µF / 50 V | 0402 |
| C1, C10 | 2 | 10 µF | 0402 |
| C20, C21 | 2 | 4.7 µF / 50 V | 0603 |
| C7, C9 | 2 | TBD | 0402 |


## how to assemble

Gets hand hands on custom pcb as well as with all components solder them and join oter components like vibrator motor , battery , and a display late that 3d printed cases put them together join them and screw it 
 later upload the firmware and wait to gt upload you can use ardino ide and wallah you have your own customized ESP-Watch
## Cost
 
Total Cost=(components+pcb+casing+display+ battery) + shipping + Custom Taxes)

 Total Cost=$23+$8+3$+$17+$0.5)+$34+(Custom may vary)
 
 Total Cost=$85.5 without customs taxes


## License

This project is licensed under the Apache License 2.0.
See [LICENSE](LICENSE).
