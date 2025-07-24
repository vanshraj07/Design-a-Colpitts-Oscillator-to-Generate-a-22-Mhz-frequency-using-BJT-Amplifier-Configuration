#Colpitt Oscillator ⚡🎛️
Overview
This project showcases the design, simulation, and hardware implementation of a Colpitt Oscillator intended to generate a 22 MHz sinusoidal signal using a BJT amplifier configuration. The oscillator leverages the LC tank circuit and feedback through capacitive voltage division to sustain oscillations — widely used in RF generation circuits.
Key Features
🔩 Hardware Components

Transistor: 2N2222 (NPN BJT)

Capacitors: 100 nF, 100 pF

Inductor: 1 µH

Resistors: 1 kΩ, 1.5 kΩ, 2.2 kΩ, 5 kΩ, 10 kΩ

📐 Oscillator Design

Capacitive divider for feedback

Tunable high-frequency operation

Theoretical frequency ≈ 22.5 MHz

Gain stability designed using equal capacitor values (C1 = C2 = 100 pF)

🔧 Amplifier Calculations

Common-emitter BJT configuration

Gain > 1 to satisfy Barkhausen criterion

Ensured transistor operation in the active region

🧪 Simulation & Verification

Circuit simulated using LTspice

Observed both transient and steady-state responses

Frequency validated through waveform inspection

🛠️ Hardware Prototyping

Assembled on breadboard and perfboard

Verified output via oscilloscope

Tackled parasitic effects through tighter connections

Tech Stack
Design Platform: LTspice

Prototyping: Breadboard & Perfboard

Measurement: Oscilloscope

Component Selection: Standard discrete components (resistors, capacitors, inductor, BJT)

Getting Started
Prerequisites
Basic electronics tools: Breadboard, soldering iron, jumper wires

Components listed above

LTspice for simulation

Oscilloscope for waveform observation

Setup Steps
Assemble Circuit
Build the Colpitt Oscillator circuit based on the schematic using BJT amplifier and LC feedback.

Simulate on LTspice
Validate frequency generation and phase relationships.

Prototype on Perfboard
Reduce parasitic effects by soldering connections.

Observe Output
Use oscilloscope to verify clean 22.5 MHz sinusoidal waveform.

Project Structure
bash
Copy
Edit
colpitt-oscillator/
│
├── design/
│   ├── calculations.pdf       # Frequency & gain derivation
│   └── schematic.png          # Hand-drawn or software-generated
│
├── simulation/
│   └── ltspice_project.asc    # LTspice simulation files
│
├── hardware/
│   ├── breadboard.jpg         # Circuit on breadboard
│   ├── perfboard.jpg          # Soldered prototype
│   └── waveform.png           # Oscilloscope output
Contributors
👤 Abhijeet Parmar - 230002001
👤 Rudraksha Harshal Amar - 230002061
👤 Vansh Raj Singh - 230002079
👤 Vansh Sabharwal - 230002080
👤 Aditya Gandhra - 230002004
Acknowledgments
🙏 LTspice – For powerful simulation capabilities
🔋 2N2222 Transistor – Reliable BJT for oscillator designs
🔬 IIT Indore Analog Lab – For lab support and guidance
🧰 Perfboard Prototyping – For solving parasitic challenges
 
