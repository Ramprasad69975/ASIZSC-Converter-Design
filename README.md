# ASIZSC Converter – Simulation & PCB Design

## Overview

This project documents the step-by-step development of a power electronics converter, starting from a basic Boost Converter and progressing toward the design of an Advanced Switched-Inductor Z-Source Converter (ASIZSC).

The work was carried out in three major stages:

1. Basic Boost Converter design and analysis
2. ASIZSC converter modelling and simulation in MATLAB/Simulink
3. Schematic and PCB design of the ASIZSC converter using KiCad

The project helped in understanding the transition from converter-level concepts and simulation to practical hardware-oriented PCB design.

---

## Project Development

### Stage 1 – Basic Boost Converter

The project initially started with the design and analysis of a conventional Boost Converter.

The basic converter was studied to understand:

- Boost converter operating principle
- Inductor and capacitor selection
- MOSFET switching
- Duty-cycle control
- Output voltage characteristics
- Continuous conduction operation
- Switching behaviour

The converter was modelled and analysed before moving toward the more advanced ASIZSC topology.

---

### Stage 2 – ASIZSC Converter Simulation

After studying the conventional Boost Converter, the project was extended to an **Advanced Switched-Inductor Z-Source Converter (ASIZSC)**.

The ASIZSC converter was modelled and simulated using **MATLAB/Simulink**.

The simulation involved:

- Switched-inductor network
- MOSFET switching stage
- Diode network
- Capacitor network
- Output filtering
- PWM-based switching
- Analysis of input and output behaviour

MATLAB/Simulink was used to study the converter operation and verify the circuit behaviour before proceeding to PCB development.

---

### Stage 3 – ASIZSC Schematic & PCB Design

After completing the converter-level simulation, the ASIZSC circuit was translated into a practical hardware design using **KiCad**.

The schematic was developed with:

- Three IRFP460 MOSFETs
- MUR640 diodes
- Switched-inductor networks
- Input and output capacitors
- Gate-driver interfaces
- Output filtering
- Load connection

The schematic was then converted into a PCB layout with consideration for component placement, power routing, high-current paths, and external gate-driver connections.

---

## Key Features

- Conventional Boost Converter study as the starting point
- Advanced Switched-Inductor Z-Source Converter topology
- MATLAB/Simulink converter simulation
- 3-MOSFET switching stage
- External gate-driver interface
- Custom footprints for large inductors
- Power-oriented PCB routing
- Through-hole and SMD components
- 3D PCB visualization
- Gerber files prepared for fabrication

---

## Hardware

- IRFP460 MOSFET × 3
- MUR640 diode × 2
- 80 µH inductors × 2
- 1 mH inductors × 2
- 33 µF capacitors × 2
- 330 µF output capacitor
- 144 Ω load resistor
- External gate-driver interface

---

## Tools Used

### Simulation
- MATLAB
- Simulink

### PCB Design
- KiCad Schematic Editor
- KiCad PCB Editor
- KiCad 3D Viewer
- KiCad Gerber Viewer

---

## Design Workflow

```text
Basic Boost Converter
        ↓
Converter Analysis
        ↓
ASIZSC Converter Development
        ↓
MATLAB/Simulink Simulation
        ↓
Circuit Schematic
        ↓
Footprint Assignment
        ↓
PCB Component Placement
        ↓
PCB Routing
        ↓
3D PCB Verification
        ↓
Gerber Generation
