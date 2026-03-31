# PCB Designs

A collection of PCB projects designed using KiCad 9 by Kavin Barath S.

---

## Projects

### 1. Breadboard Power Supply

A multi-rail regulated DC power supply designed for breadboard prototyping.

**Features**
- 3.3V output — LM317L (SOT-89) adjustable linear regulator
- 5V output — LM7805 (TO-220) fixed linear regulator
- 12V pass-through from DC input
- Barrel jack DC input with EG1218 power switch
- LED power indicators per rail
- Screw terminal and pin header outputs

**Schematic & Layout:** `Bread_Board_Power_Supply/`

---

### 2. Tiny Solar Power Supplier

A compact boost-converter PCB for harvesting energy from a small solar panel and stepping it up to a usable output voltage.

**Features**
- AP3015AKTR-G1 boost converter IC
- ASPI-0630LR-100M-T15 100µH power inductor
- SS14 Schottky diode for rectification
- 2N7002 N-channel MOSFET
- 2-pin connectors for solar input and regulated output
- Optimised layout for minimal switching-loop area and low EMI

**Schematic & Layout:** `tiny_solar_power_supplier/`

---

## Tools Used

- [KiCad 9](https://www.kicad.org/) — Schematic capture, PCB layout, DRC

---

## Author

**Kavin Barath S**
- GitHub: [github.com/kavinR-11](https://github.com/kavinR-11)
- LinkedIn: [linkedin.com/in/kavin-barath-s-1958b3324](https://www.linkedin.com/in/kavin-barath-s-1958b3324)
- Email: reach.kavinbarath@gmail.com
