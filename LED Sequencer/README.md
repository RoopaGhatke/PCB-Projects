This project presents a 10-LED sequential chaser circuit designed using a NE555 timer as a clock pulse generator and a CD4017 decade counter to drive 10 LEDs in a timed sequence. 
The project follows the design outlined in popular electronics tutorials and demonstrates fundamental principles of digital timing, counters, and visual indicators using discrete components.

Features
1. Sequential LED Lighting (Lights 10 LEDs one-by-one in a loop)
2. ICs Used:
NE555DR Timer (configured in astable mode to generate clock)
CD4017BM Decade Counter (10 decoded outputs)
3. Components:
10x Red Diffused LEDs
10x Current-limiting resistors (1 kΩ) for each LED
Timing resistors (2.2 kΩ, 10 kΩ) and capacitor (1 µF) for 555 timing
50 kΩ variable resistor for frequency adjustment
4. Power Supply:
VCC and GND pins via 2-pin header
Operates at 5 V – 12 V (regulated)
5. Design Best Practices:
Decoupling capacitors at IC power pins
Proper grounding for digital ICs and LEDs
Optimized double-layer routing for easy prototyping

Files Included
Schematic – LEDSequencer.SchDoc
PCB – LEDSequencer.PcbDoc
BOM– Bill of Materials
Images of schematic, layout, 3D view

The complete design includes the schematic, PCB layout, double-layer board routing and component placement - all created using Altium Designer as part of my hands-on learning journey.
