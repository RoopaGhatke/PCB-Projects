This project presents a custom 4-layer ESP32-S3 development board designed using Altium Designer, built around the ESP32-S3-MINI-1-N8 module. The board integrates USB-C connectivity, 
an FTDI-based USB-to-UART interface, and a robust power supply system, making it suitable for low-power IoT and embedded development.

Features
1. ESP32-S3-MINI-1-N8
2. FT231XQ-R USB-to-UART Interface:
Full-speed USB to serial communication
Connected via USB-C for ease of flashing/debugging
3. USB-C Interface (x2):
One for FTDI-UART, one for direct USB to ESP32-S3
Includes ESD protection diodes (TVS)
Proper USB signal routing with impedance control
4. Reset and Boot Buttons (Tactile switches for flashing/boot mode)
5. Power Supply System
   TL1963A-33 LDO Regulator: 5V to 3.3V conversion; Low dropout, high current support (up to 1.5A)
   VBUS sensing circuit for self-powered configuration
   Power selection jumpers & filtering capacitors
6. GPIO Access and Expandability
   Dual 24-pin headers to break out: Digital I/O, SPI, UART, I2C, PWM, ADC, DAC, etc.
7. User LED and Power LED included for testing
8. Design Practices
   Controlled impedance routing for USB signals
   Decoupling capacitors placed close to power pins
   Clear power/ground separation and star grounding
   Compact, professional 4-layer layout with power and ground planes

Files Included
Schematic – ESP32_USB_C.SchDoc
PCB– ESP32_USB_C.PcbDoc
BOM– Bill of Materials
Pick Place for ESP32_USB_C (Prototype)
Images of schematic, PCB layout and 3D view

This project was developed from scratch by following the design methodology taught in the YouTube tutorial “How to Make a Custom ESP32 Board in Altium Designer” by Robert Feranec.
It served as a self-learning exercise to gain in-depth skills in embedded system PCB design, high-speed USB routing and signal integrity practices.
