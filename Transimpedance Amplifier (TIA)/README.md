Transimpedance Amplifier with Photodiodes – Circuit Design Lab

This repository documents the week-long Circuit Design Laboratory course project where I designed, simulated, fabricated, and tested a Transimpedance Amplifier (TIA) using photodiodes. 
The work involved both hardware and simulation aspects using KiCad and PCB prototyping tools.

Project Overview
The goal was to design a transimpedance amplifier circuit to convert photocurrent from a photodiode into a measurable voltage. 
The project was carried out step by step — from schematic design to simulation, PCB layout, fabrication, soldering and final testing.

Tools Used
KiCad for schematic design, simulation (DC, AC, and transient), and PCB layout
PCB etching tools for single and double-layer board fabrication
Basic electronics lab tools for assembly and testing (multimeter, soldering iron, etc.)

Key Design Highlights

1. Circuit Type: Transimpedance amplifier using photodiodes
2. Simulation:
   DC Analysis: Verified operating point and biasing
   AC Analysis: Observed frequency response and gain-bandwidth
   Transient Analysis: Verified dynamic behavior to input signal changes
3. PCB Layouts:
   Designed both single-layer and double-layer PCBs
   Included placement of photodiodes, op-amp, feedback resistor and capacitor, power supply pins, and headers

Fabrication & Testing Insights

1. Double-Layer PCB Issues:
   Over-etching due to prolonged etching bath exposure
   Heat damage during soldering caused pin header sinking
   Via placement too close to traces led to short circuits

2. Single-Layer PCB Success:
   Proper etching and trace definition
   Stable soldering and component mounting
   Functional test successful with clean output response

Visual Documentation
Images are available in the /images directory:
Double-layer board (defective): shorted vias, over-etching
Single-layer board (working): clean layout, successful testing

Learnings
Hands-on experience with full PCB design cycle
Impact of layout decisions on board performance
Importance of thermal control during soldering
Troubleshooting real-world fabrication errors
Value of simulation in verifying design before manufacturing
