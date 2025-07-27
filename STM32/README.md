This repository showcases a custom-designed STM32-based development board, featuring both schematic and PCB layout files created using KiCad. 
While the conceptual design was inspired by an online tutorial by Phil’s Lab, all schematic drawing and PCB layout work were done independently to reinforce hands-on learning.

Overview
This project revolves around the STM32F103C8T6 microcontroller, a widely-used ARM Cortex-M3 chip that serves as an excellent entry point for embedded systems and bare-metal firmware development.
The board provides all the basic peripherals required to begin STM32 experimentation, flashing and GPIO testing.

Features
1. SWD (Serial Wire Debug) Header for programming and in-circuit debugging
2. 3.3V Voltage Regulator for clean power supply
3. Reset Button to manually restart the MCU
4. User Button connected to GPIO for input testing
5. Status LED for simple visual output
6. 16 MHz Crystal Oscillator with load capacitors for clock stability

Design Details
Schematic: Created independently by referencing the block design principles shown in Phil’s Lab tutorial.
PCB Layout: Fully original – includes custom component placement, net class setup, design rule checking and optimized 2-layer routing.
Tool Used: KiCad (v9)

Files Included
Schematic             # KiCad .sch files
PCB                   # .kicad_pcb layout files
BOM                   # Bill of Materials
Image                 # 3D previews

The board was designed as a 2-layer PCB, focusing on compact layout, proper signal routing, and practical hardware bring-up considerations. 
It was developed from scratch in KiCad as part of a personal learning exercise in microcontroller board design and hardware prototyping.

