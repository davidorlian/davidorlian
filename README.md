# David Orlian

I'm drawn to the layer where hardware meets software — where understanding both sides is what actually solves the problem.

From RTL and synthesis to verified hardware, and from bare-metal firmware to a web UI running on the chip itself. I like knowing what's happening at every level of the stack.

Most of my work lives close to the metal — digital design, embedded systems, RF communication, HW/SW integration. I don't just write code; I debug the interaction between layers.

---

## Stack

| Domain | Tools & Languages |
|---|---|
| HDL / RTL | Verilog, VHDL |
| Simulation & Synthesis | ModelSim, Vivado (Artix-7) |
| Embedded | C/C++, ESP32, Arduino, PlatformIO |
| Protocols | I²C, UART, RF (433MHz, HC-12) |
| General | Python, Git, Linux/UNIX |
| Web (Embedded) | HTML/CSS/JS, AsyncWebServer |

---

## Projects

### 🔷 Digital Design & FPGA

**[DES-verilog](https://github.com/davidorlian/DES-verilog)**  
Full hardware implementation of DES encryption in Verilog — pipelined architecture, complete testbenches, and synthesis results on Artix-7.

**[HDL_Projects](https://github.com/davidorlian/HDL_Projects)**  
Collection of Verilog & VHDL modules with testbenches, documentation, and synthesis scripts.

---

### 🔶 Embedded Systems & IoT

**[smart-shabbat-clock](https://github.com/davidorlian/smart-shabbat-clock)**  
ESP32-based Shabbat timer with RTC/NTP timekeeping, weekly scheduling, web UI, and RF control of remote switch units.

**[smart-shabbat-switch](https://github.com/davidorlian/smart-shabbat-switch)**  
Remote switch unit (HC-12) with Sabbath bypass logic and mains-rated switching stage — designed to be controlled by the clock above.

**[rf-shabbat-timer](https://github.com/davidorlian/rf-shabbat-timer)**  
ESP32-C3 RF timer with AsyncWebServer-based web UI, RTC scheduling, and logical ON/OFF state tracking over toggle-type RF devices.

**[oref-relay-esp32](https://github.com/davidorlian/oref-relay-esp32)**  
ESP32 relay controller triggered by Israeli Home Front Command (Oref) alerts — with local web configuration UI and heap-optimized firmware.
