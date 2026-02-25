# Linear Voltage Regulator

This repository contains the hardware design, manufacturing, and simulation files for a discrete linear voltage regulator. The project was developed using OrCAD Capture and PCB Designer Lite (Sutu Fabian - Group 431F, 2024-2025).

## 📋 Project Overview
The circuit is a transistor-based linear voltage regulator utilizing a Zener diode reference to provide a stable power output. The design includes full PSpice simulation verification and production-ready manufacturing files.

### Key Hardware Components
* **Power Pass Transistors:** QMJD32CT4G
* **Bipolar Junction Transistors (BJTs):** QBC817-25 (NPN), QBC807-25 (PNP)
* **Zener References:** BZX84-C10 (10V), BZX84-C6V2 (6.2V)

## 📂 Repository Structure

* `/Hardware` — Contains the core OrCAD design files (`.dsn` schematic, `.opj` project, and `.brd` PCB layout).
* `/Gerbers` — Contains the production-ready `.art` and `.drl` files for PCB manufacturing (Top/Bottom copper, Soldermask, Silkscreen, and Drill data).
* `/Simulation` — Contains the PSpice component models and text-based simulation results (DC Bias, Overcurrent Protection, Overvoltage Protection).

## 💻 Software Requirements
To open the source files natively, you will need:
* **OrCAD Capture** (for `.dsn` files)
* **OrCAD PCB Designer Lite** (for `.brd` files)
* Any standard Gerber Viewer to inspect the `/Gerbers` directory.
