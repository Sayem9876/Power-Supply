# 🔌 Dual Output DC Power Supply (2–24V Variable & Fixed 5V)

## 📌 Project Overview
This project involves the **design, implementation, and analysis of a dual-output regulated DC power supply** capable of providing:

- **Variable DC output:** 2 V – 24 V using **LM317**
- **Fixed DC output:** 5 V using **7805**

The system converts **AC mains voltage** into a stable and regulated DC supply using a transformer, bridge rectifier, filter capacitor, and linear voltage regulators.  
It is suitable for **laboratory experiments, testing, and educational applications**.

---

## 🎯 Project Objectives
- Convert AC mains voltage into regulated DC
- Design an adjustable power supply using LM317
- Provide a stable 5 V output for digital circuits
- Reduce ripple voltage using proper filtering
- Analyze performance using **MATLAB**
- Implement the design on **veroboard and PCB**

---

## 🧩 Components Used
- Step-down transformer (230 V → 24 V)
- Bridge rectifier
- Filter capacitor (4700 µF)
- LM317 adjustable voltage regulator
- 7805 fixed voltage regulator
- Potentiometer
- Discrete resistors and capacitors
- Multimeter and oscilloscope

---

## ⚙️ Working Principle
1. AC mains voltage is stepped down using a transformer  
2. A bridge rectifier converts AC into pulsating DC  
3. A filter capacitor smooths the DC voltage  
4. LM317 provides adjustable output from 2 V to 24 V  
5. 7805 provides a fixed and stable 5 V output  

---

## 📐 Circuit Design & Layout

### Overall Circuit Layout
![Layout](images/Layout.png)

### Variable 2–24 V Regulator Circuit
![2–24V Circuit](images/2_24V.png)

### Fixed 5 V Regulator Circuit
![5V Circuit](images/5V.png)

---

## 📊 Input and Output Waveforms

### Input AC Waveform
![Input Waveform](images/Input_Waveform.png)

### Variable Output Waveform (2 V)
![2V Waveform](images/2V_Waveform.png)

### Variable Output Waveform (23.3 V)
![23.3V Waveform](images/23_3V_Waveform.png)

### Fixed 5 V Output Waveform
![5V Waveform](images/5V_Waveform.png)

---

## 🔍 Experimental Results

### Variable Output (Minimum Voltage)
![1.9V Output](images/1_9V_Output.jpg)

### Variable Output (Maximum Voltage)
![23.9V Output](images/23_9V_Output.jpg)

### Fixed 5 V Output
![5V Output](images/5V_Output.jpg)

---

## 🧮 MATLAB Analysis

### Ripple Voltage with 4700 µF Capacitor
![Ripple 4700uF](images/Ripple_4700uF.png)

### Ripple Voltage vs Capacitance
![Ripple vs Capacitance](images/Ripple_vs_Capacitance.png)

### LM317 Output Voltage vs Potentiometer
![LM317 Output vs Potentiometer](images/LM317_Output_vs_Potentiometer.png)

### Power Dissipation in LM317
![Power Dissipation LM317](images/Power_Dissipation_LM317.png)

---

## 🛠 Hardware Implementation

### Veroboard Implementation
![Veroboard](images/Veroboard.png)

---

## 🖥 PCB Design

### PCB Routing
![PCB Routing](images/PCB_Routing.png)

### PCB Routing (Improved)
![PCB Routing II](images/PCB_Routing_II.png)

### PCB 3D Model
![PCB 3D Modelling](images/PCB_3D_Modelling.png)

---

## 📄 Documentation
A complete detailed project report is included in this repository.

---

## 👨‍💻 Authors
- **Sayem Ul Haq**
---

## 🏫 Institution
**NUST – College of Electrical and Mechanical Engineering**  
Department of Electrical Engineering

---

## 📜 License
This project is intended for **academic and educational use only**.
