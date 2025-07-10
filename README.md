# Five-Transistor OTA (Operational Transconductance Amplifier)

A compact, low-power five-transistor operational transconductance amplifier (OTA)  designed using Cadence Virtuoso and validated through simulations.

---

## Overview

This OTA design was completed as part of an analog design exploration project. The objective was to achieve:

- Moderate voltage gain suitable for front-end analog processing
- High bandwidth for fast signal response
- Low power consumption for integration in energy-sensitive systems

---

## Specifications

| Parameter                  | Value               |
|---------------------------|---------------------|
| Architecture              | Five-transistor OTA |
| Gain                      | >18 dB              |
| Bandwidth (−3 dB)         | 558 MHz             |
| Gain-Bandwidth Product    | 2.58 GHz            |
| Output Swing              | >1.1 V              |
| Load                      | 100 fF capacitor    |
| Power Consumption         | <2 mW               |

---

## Tools Used

- **Cadence Virtuoso** for schematic capture and simulation
- **Spectre**  for AC and transient analysis

---

## Simulations

- **AC Analysis**  
  Verified midband gain, −3 dB bandwidth, and GBW under a 100 fF capacitive load.

- **Transient Analysis**  
  Confirmed large signal swing >1.1 V





