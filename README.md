# Colpitt Oscillator ⚡📻

## Overview  
This project showcases the design, simulation, and hardware implementation of a **Colpitt Oscillator** designed to generate a **22 MHz sinusoidal signal** using a **BJT amplifier configuration**. The oscillator uses an LC tank circuit with capacitive feedback, commonly used in RF signal generation circuits.

---

## 🔑 Key Features

### 🔧 Hardware Components  
- **Transistor:** 2N2222 (NPN BJT)  
- **Capacitors:** 100 nF, 100 pF  
- **Inductor:** 1 µH  
- **Resistors:** 1 kΩ, 1.5 kΩ, 2.2 kΩ, 5 kΩ, 10 kΩ

### 🌀 Oscillator Design  
- Capacitive divider for feedback  
- Tunable high-frequency operation  
- Theoretical frequency: **≈ 22.5 MHz**  
- Gain stability ensured using **C₁ = C₂ = 100 pF**

### 📈 Amplifier Calculations  
- Common-emitter BJT configuration  
- Gain **> 1** to satisfy **Barkhausen Criterion**  
- Biasing ensures transistor stays in **active region**

### 🧪 Simulation & Verification  
- Circuit simulated using **LTspice**  
- Verified **transient** and **steady-state** behavior  
- Observed clean oscillations in output waveform

### 🛠️ Hardware Prototyping  
- Built on both **breadboard** and **perfboard**  
- Measured output using **oscilloscope**  
- Addressed parasitic capacitance through tighter soldering

---

## 🧱 Project Structure

colpitt-oscillator/
│
├── design/ # Handwritten & theoretical design files
│ └── calculations.pdf
│
├── simulation/ # LTspice project
│ └── colpitt.asc
│
├── hardware/ # Physical build and test results
│ ├── breadboard.jpg
│ ├── perfboard.jpg
│ └── waveform.png


---

## 👥 Contributors

- **Abhijeet Parmar** – Roll No: 230002001  
- **Rudraksha Harshal Amar** – Roll No: 230002061  
- **Vansh Raj Singh** – Roll No: 230002079  
- **Vansh Sabharwal** – Roll No: 230002080  
- **Aditya Gandhra** – Roll No: 230002004  

---

## 🙏 Acknowledgments

- **LTspice** – Circuit simulation  
- **IIT Indore Analog Lab** – Lab support & guidance  
- **Standard discrete components** – From local electronics stores  
- **Dead-bug wiring & perfboard** – To mitigate parasitic issues

---

## 📝 Notes

> 📌 *We faced distortion due to parasitic capacitance on the breadboard. Switching to a perfboard with tighter soldered connections significantly improved output waveform quality.*

---

