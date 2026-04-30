# David Orlian

Electrical & Electronics Engineering graduate-track developer working on hardware-oriented systems, from RTL and FPGA-oriented digital design to embedded firmware and software tools for real-world hardware integration.

---

## Main Projects

### [DES in Verilog](https://github.com/davidorlian/DES-verilog)

A complete DES encryption core implemented in Verilog, following the standard 16-round Feistel architecture.  
The repository includes modular RTL for the datapath and key schedule, self-checking testbenches, Python-generated reference vectors, ModelSim simulation scripts, and FPGA synthesis / timing results for an Artix-7 target.

---

### Smart Shabbat System

A hardware/software system for scheduled Shabbat-mode load control, built around a central ESP32 controller and a remote ATmega328P switch unit.

#### [Central controller — smart-shabbat-clock](https://github.com/davidorlian/smart-shabbat-clock)

ESP32-based scheduling controller with RTC/NTP timekeeping, local Web UI, LCD status display, persistent weekly scheduling, and HC-12 RF communication to remote switch units.

#### [Remote switch unit — smart-shabbat-switch](https://github.com/davidorlian/smart-shabbat-switch)

Companion remote switch unit based on ATmega328P / Arduino AVR firmware.  
The unit receives HC-12 RF commands, senses the AC/load state through opto-isolated detection, and controls the local load through relay-based switching logic.

---

### [Smart Geiger OCR Monitor](https://github.com/davidorlian/smart-geiger-ocr-monitor)

A Python-based camera OCR monitor for reading a handheld Geiger counter LCD without modifying the meter hardware.  
The system uses one-time ROI calibration, a 7-segment-oriented OCR pipeline, Tesseract fallback, threshold monitoring, measurement logging, and separate PC/Raspberry Pi operating modes.

---

### [Oref Relay ESP32](https://github.com/davidorlian/oref-relay-esp32)

An ESP32-based relay controller that polls Home Front Command alert feeds over HTTPS, parses JSON alert data, matches alerts against a configured area, and drives a relay according to alert categories.  
The firmware includes local Web UI configuration, persistent settings with ESP32 Preferences, setup-AP fallback, LED status indication, and relay output control.

---

## Additional HDL Work

### [HDL Projects](https://github.com/davidorlian/HDL_Projects)

Smaller Verilog and VHDL building blocks and testbenches covering combinational logic, sequential logic, counters, registers, UART-related modules, and other RTL practice work.

---

## Prototype / Experimental Work

### [RF Shabbat Timer Prototype](https://github.com/davidorlian/rf-shabbat-timer)

Earlier ESP32-C3 prototype exploring RTC scheduling, local Web UI control, and RF transmission to a toggle-based receiver with no direct state feedback.

---

## Technical Stack

### Hardware / RTL

Verilog, VHDL, digital design, FPGA-oriented development, ModelSim, Vivado

### Embedded

ESP32, ATmega328P / AVR, Arduino framework, RTC modules, RF modules, relays, sensors, LCDs

### Software / Tooling

Python, OpenCV, Tesseract OCR, Git, JSON parsing, local web interfaces, test automation

---

## Contact

[LinkedIn](https://www.linkedin.com/in/david-orlian)