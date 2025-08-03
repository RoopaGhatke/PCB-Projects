This repository showcases a custom-designed RP2040-based development board, featuring both schematic and PCB layout files created using KiCad.
While the conceptual design was inspired by general community examples and official documentation, all schematic drawing and PCB layout work were done independently to reinforce hands-on learning.

Overview
This project revolves around the RP2040 microcontroller, a dual-core ARM Cortex-M0+ chip developed by Raspberry Pi.
The board includes all the essential components required for flashing, debugging and GPIO testing, making it ideal for embedded systems experimentation.

Features
1. USB Micro-B connector for power and programming
2. 3.3V LDO Voltage Regulator for clean power supply
3. External 12 MHz Crystal Oscillator for clock stability
4. 16MB QSPI Flash memory for storing firmware
5. Full GPIO access via dual-row headers

Design Details
Schematic: Created independently by referencing RP2040 datasheets and design guidelines
PCB Layout: Fully original – includes manual component placement, DRC checks and optimized 2-layer routing
Tool Used: KiCad (v9.0.3)

Files Included
Schematic - KiCad .sch files
PCB - KiCad .kicad_pcb layout files
Images - 3D board view, pcb layout

The board was designed as a 2-layer PCB, focusing on compact layout, proper signal routing and practical hardware bring-up considerations.
It was developed from scratch in KiCad as part of a personal learning exercise in microcontroller board design and embedded hardware prototyping.
