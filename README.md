# Geotechnical-PCB

A custom-designed PCB for the Science Subsystem of a planetary rover, developed to support geotechnical and soil analysis experiments through integrated control of scientific instruments and actuators. The board is designed around two ESP32-S3 microcontrollers, which coordinate subsystem operations and communicate via SPI to ensure reliable and modular control.

Key features include:

- Dual ESP32-S3 architecture for distributed control, sensor management, and inter-board communication.
- TB6612FNG motor drivers for controlling Kamoer peristaltic pumps and DC motors used in sample handling and reagent delivery systems.
- A4988 stepper motor drivers for precise positioning and motion control of scientific mechanisms.
- Integrated power distribution and management circuitry for efficient subsystem operation.
- Sensor interfacing and data acquisition capabilities for geotechnical and soil characterization experiments.
- Modular design to enable seamless integration with rover onboard computers and science payloads.
