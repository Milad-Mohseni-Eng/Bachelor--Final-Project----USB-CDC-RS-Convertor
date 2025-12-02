Bachelor Final Project — USB-to-RS232 Converter (AT90USB82/162)

Overview

This project implements a USB-to-Serial (RS-232) converter using the AT90USB82/162 microcontroller with native USB support.
The system enumerates as a virtual COM port, allowing industrial and legacy RS-232 devices to communicate with modern PCs via USB.

Key Features & My Contributions

- Developed the firmware in C using WinAVR, including USB CDC class implementation and dynamic UART configuration up to 57,600 bps.

- Designed the hardware interface for USB lines, UART level-shifting, and reliable PD2/PD3 communication.

- Tested the system with HyperTerminal and multiple programmers and industrial devices.

- Packaged the project with drivers, source code, and schematic documentation.


Technologies Used

   C programming (WinAVR compiler)

   AT90USB82 / AT90USB162 (8-bit AVR with USB controller)

   USB CDC class, virtual COM port

   UART/RS-232 communication

   USB bootloader flashing via FLIP

   Hardware schematic design & debugging
