# Mouse Design

This repository contains the electrical and mechanical design work for a compact 2.4 GHz wireless computer mouse. The focus of the project is on developing a **low‑noise, power‑efficient electrical subsystem** powered from a single‑cell 3.7 V 80 mAh LiPo battery with USB‑C charging.

## Project Objectives
This project aims to design a compact, low-noise, and power-efficient electrical subsystem for a 2.4 GHz wireless mouse powered by a 3.7 V 80 mAh LiPo battery with USB-C charging. The objective is to implement a reliable single-cell LiPo charging circuit with safe CC/CV operation, enable simultaneous operation while charging, and generate a clean, stable 3.3 V rail suitable for sensitive RF and digital circuitry. The design emphasizes low quiescent current for extended battery life, proper power domain isolation to minimize EMI and RF interference, robust input protection, and practical battery monitoring for system intelligence. The overall goal is to build a modular, production-ready power architecture that balances efficiency, simplicity, RF integrity, and reliability. The mechanical system of the mouse will be developed for the complete assembly.


1. **Battery management and charging** – implement a reliable single‑cell LiPo charging circuit supporting CC/CV operation and allowing the mouse to operate while charging. Ensure robust input protection and USB‑C compliance.
2. **Power conversion** – generate a clean, stable 3.3 V supply for RF and digital components. Emphasize low quiescent current to maximize standby and active battery life.
3. **EMI/RF integrity** – isolate power domains and minimize noise coupling between the RF transceiver, digital logic, and power circuitry.
4. **Protection and monitoring** – add over‑voltage, reverse‑polarity, and short‑circuit protection on the input, and include practical battery voltage/current monitoring for system intelligence and safety.
5. **Modularity and manufacturability** – build a production‑ready power architecture that balances efficiency, simplicity, and reliability within the constraints of a compact mouse form factor.
6. **Mechanical integration** – develop the mechanical system and enclosures so that the electrical subsystem and all components can be assembled into a finished mouse.

## Design Philosophy

- **Low noise**: Critical for the RF link and optical/laser sensor performance.
- **Low quiescent current**: Extend battery life to many weeks of normal use.
- **Safe and reliable**: Use established charging ICs and design practices to protect the cell and user.
- **Modular**: Separate power, RF, sensor, and mechanical domains to ease testing and future upgrades.

## Folder Structure

- `Project/` – design files, schematics, and BOMs.
- `MechanicalSystem Design/` – CAD files and mechanical assemblies.
- `Research Documents/` – datasheets, calculations, and reference material.

## Next Steps

Continue detailed schematic capture, PCB layout, and mechanical modelling. Validate power architecture on prototype boards, then iterate toward a production‑ready design.

---

*Last updated: February 26, 2026*