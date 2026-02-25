# Linear Voltage Regulator

This repository contains the hardware design files for a discrete linear voltage regulator. The project includes the full schematic capture and PCB layout, designed as part of the 2024-2025 academic curriculum (Sutu Fabian - Group 431F).

## 📋 Project Overview

The circuit is a transistor-based linear voltage regulator utilizing a Zener diode reference to provide a stable power output. It features power dissipation analysis markers and is routed on a compact printed circuit board.

### Key Hardware Components
* **Power Pass Transistors:** QMJD32CT4G
* **Bipolar Junction Transistors (BJTs):** QBC817-25 (NPN), QBC807-25 (PNP)
* **Zener References:** BZX84-C10 (10V), BZX84-C6V2 (6.2V)
* **Custom Footprints:** Custom padstacks included (`PAD_5X25`)

## 📂 Repository Contents

The repository is structured to separate the core Cadence/OrCAD source files from the generated outputs and documentation:

* `PROIECT.dsn` - The main OrCAD Capture schematic database.
* `PROIECT.opj` - The OrCAD project manager file.
* `allegro/PROJECTU.brd` - The OrCAD PCB Designer board layout file.
* `PAD_5X25.dra` / `pad_5x25.psm` - Custom footprint and padstack files required to view and edit the PCB layout.

*(Note: Temporary simulation logs, session journals, and local configuration files are intentionally excluded from this repository.)*

## 💻 Software Requirements

To open and modify the source files in this repository, you will need:
* **OrCAD Capture** (v16.6 or compatible) for the `.dsn` schematic.
* **OrCAD PCB Designer Lite** for the `.brd` layout.

## 🚀 How to Open

1. Clone this repository to your local machine.
2. Ensure `PROJECTU.brd` is located in the `allegro` folder relative to the schematic.
3. Open `PROIECT.opj` in OrCAD Capture to view the schematic and project hierarchy.
4. Open `allegro/PROJECTU.brd` in OrCAD PCB Designer to view or edit the board layout.
