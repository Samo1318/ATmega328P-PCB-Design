# ATmega328P-PCB-Design
ATmega328P based PCB designed EasyEDA for embedded system applications. Features an 8MHz crstal oscillator, reset circuitary, 4-digit seven segment display, LED indicators, push buttons, programming headers and essential supporting components for micrcontroller interfacing and hardware development. 
# ATmega328P Custom PCB – Embedded System Board

![EasyEDA](https://img.shields.io/badge/EasyEDA-008B8B?style=for-the-badge&logo=easyeda&logoColor=white)
![ATmega328P](https://img.shields.io/badge/ATmega328P-005C8A?style=for-the-badge&logo=arduino&logoColor=white)
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)
![Embedded C](https://img.shields.io/badge/Embedded_C-00599C?style=for-the-badge&logo=c&logoColor=white)

---

## 📌 Overview

This project presents a **custom PCB** designed using **EasyEDA** based on the **ATmega328P** microcontroller for embedded system applications. The PCB was developed in an **Ubuntu environment** and integrates essential hardware components including clock generation, reset circuitry, display interfacing, and input/output controls.

The project demonstrates practical **PCB design**, **microcontroller interfacing**, and **embedded electronics implementation**.

---

##  Features

| Feature | Description |
|---------|-------------|
|  **Microcontroller** | ATmega328P-PU |
|  **Clock Source** | 8MHz Crystal Oscillator |
|  **Reset Circuit** | Push button with pull-up resistor |
|  **Display Interface** | 4-Digit Seven Segment Display |
|  **LED Indicators** | Status and power indication |
|  **Push Button Inputs** | User input controls |
|  **Programming Headers** | UART/FTDI programming interface |
|  **Passive Components** | Capacitors, resistors for stability |
|  **Compact PCB Design** | Optimized layout for prototyping |

---

##  Microcontroller: ATmega328P

| Parameter | Value |
|-----------|-------|
| Core | AVR 8-bit |
| Clock Speed | 8 MHz (external crystal) |
| Flash Memory | 32 KB |
| SRAM | 2 KB |
| EEPROM | 1 KB |
| Operating Voltage | 5V |
| Package | DIP-28 |

---

##  Hardware Components

| Component | Quantity | Purpose |
|-----------|----------|---------|
| ATmega328P-PU | 1 | Main microcontroller |
| 8MHz Crystal Oscillator | 1 | Clock signal generation |
| Capacitors (22pF, 0.1µF, 10µF) | Several | Circuit stabilization |
| Resistors (220Ω, 10kΩ) | Several | Current limiting, pull-up |
| Push Buttons | 3+ | User inputs + reset |
| LEDs | 2+ | Status indication |
| Pin Headers | As needed | Programming and interfacing |
| 4-Digit Seven Segment Display | 1 | Output display module |
| Voltage Regulator (5V) | 1 | Power regulation |

---

##  Software Used

| Software | Purpose |
|----------|---------|
| **EasyEDA** | PCB schematic and layout design |
| **Ubuntu Linux** | Development environment |
| **Embedded C** | Programming language |
| **avrdude** | Microcontroller flashing |

---

## Development Environment

| Item | Specification |
|------|---------------|
| Operating System | Ubuntu (22.04 / 24.04) |
| PCB Design Software | EasyEDA |
| Microcontroller | ATmega328P |
| Programming Language | Embedded C |
| Programmer | USB-to-UART (FTDI/CH340) |

---

## 📁 Project Structure
