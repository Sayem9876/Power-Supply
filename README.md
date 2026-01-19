# 🔌 Dual Output DC Power Supply (2–24V & Fixed 5V)

## 📌 Project Overview
This project presents the design and implementation of a **dual output regulated DC power supply**.  
It provides:
- **Variable DC output:** 2 V – 24 V using **LM317**
- **Fixed DC output:** 5 V using **7805**

- The power supply converts **230 V AC mains** into a stable and regulated DC output using a transformer, bridge rectifier, filter capacitor, and voltage regulator stages. The design ensures low ripple, stability, and reliable performance, making it suitable for laboratory and educational use.

- ## 🎯 Project Objectives
- Convert AC mains voltage into regulated DC
- Provide adjustable and fixed voltage outputs
- Minimize ripple voltage
- Ensure stable operation under load
- Design and implement PCB and veroboard layouts

- ## 🧩 Components Used
- Step-down transformer (230 V → 24 V)
- Bridge rectifier (2W06G)
- Filter capacitor (4700 µF)
- LM317 adjustable voltage regulator
- 7805 fixed voltage regulator
- Potentiometer (5 kΩ)
- Resistors and capacitors
- Measuring instruments (multimeter, oscilloscope)

- ## ⚙️ Working Principle
1. The transformer steps down the AC mains voltage.
2. The bridge rectifier converts AC into pulsating DC.
3. The filter capacitor smooths the DC by reducing ripple.
4. The LM317 provides an adjustable DC output from 2 V to 24 V.
5. The 7805 regulator provides a constant 5 V DC output.
6. Regulated DC outputs are obtained for safe electronic applications.

## 📐 Circuit Schematics

### Variable 2–24 V DC Power Supply (LM317)
![Variable 2–24V Schematic](circuit/Variable_2_24V_Schematic.png)

### Fixed 5 V DC Power Supply (7805)
![Fixed 5V Schematic](circuit/Fixed_5V_Schematic.png)
