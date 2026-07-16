# 🌬️ Wind Turbine Powered DC Generator for Rural Electrification

> A renewable energy engineering project demonstrating electricity generation using a wind-driven DC generator to power a miniature village.

![Project Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![Discipline](https://img.shields.io/badge/Engineering-Electrical-blue)
![Software](https://img.shields.io/badge/Software-Proteus-orange)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

---

## 📖 Project Overview

This project demonstrates the generation of electrical energy using a **wind-driven DC generator**. Airflow from a hair dryer or air pump simulates wind, causing the turbine to rotate and drive the generator.

The generated electricity powers a miniature village consisting of buildings and traffic lights (LEDs). Experimental measurements were taken at three different wind speeds to investigate the relationship between turbine speed and electrical output.

The project highlights the potential of renewable energy technologies to reduce dependence on fossil fuels and provide sustainable electricity solutions.

---

## 🎯 Objectives

- Design and construct a small-scale wind turbine.
- Generate electricity using a DC generator.
- Power LEDs representing buildings and traffic lights.
- Measure voltage, current and power at different wind speeds.
- Compare theoretical and experimental results.

---

## 🌍 Background

Many countries, including South Africa, experience frequent electricity shortages due to increasing energy demand. Renewable energy sources such as wind offer sustainable alternatives that reduce greenhouse gas emissions while improving energy security.

This project demonstrates how wind energy can be converted into electrical energy through electromagnetic induction.

---

# 🛠 Equipment

- Hair Dryer / Air Pump
- Digital Multimeter
- Soldering Iron
- Connecting Wires

---

# 🔩 Components

- DC Generator
- 100 Ω Resistor
- Red LEDs
- Green LEDs
- Insulated Wires

---

# 🔌 Circuit Description

The DC generator supplies power to:

- 100 Ω resistor connected in series
- Three LEDs connected in parallel
- Building LEDs representing village lighting

The resistor limits current to protect the LEDs from excessive voltage.

---

# ⚙️ Working Principle

1. Wind rotates the turbine.
2. The turbine drives the DC generator.
3. Mechanical energy is converted into electrical energy.
4. Increasing turbine speed increases the generated EMF.
5. The generated electricity powers the LEDs.

---

# 📊 Experimental Results

## DC Generator Output

| Speed | Current (mA) | Voltage (V) | Power (mW) |
|-------|-------------:|------------:|-----------:|
| Low | 4.3 | 2.50 | 10.75 |
| Medium | 49.8 | 6.93 | 345.11 |
| High | 74.4 | 9.69 | 720.94 |

---

## Resistor Measurements

| Speed | Current (mA) | Voltage (V) | Power (mW) |
|-------|-------------:|------------:|-----------:|
| Low | 5.3 | 0.81 | 4.29 |
| Medium | 52.6 | 5.03 | 264.58 |
| High | 64.0 | 5.40 | 345.60 |

---

# 📈 Results Summary

- Voltage increased with wind speed.
- Current increased with generator speed.
- Maximum generated voltage: **9.69 V**
- Maximum generated power: **720.94 mW**
- LEDs illuminated brighter at higher wind speeds.
- The 100 Ω resistor successfully protected the LEDs.

---

# ⚠ Challenges

During the initial construction, the resistor was accidentally omitted from the circuit, causing the LEDs to burn out due to excessive current.

The circuit was reconstructed with the resistor installed, after which the project operated successfully.

---

# ✅ Conclusion

The project successfully demonstrated the conversion of wind energy into electrical energy using a DC generator. As turbine speed increased, the generated voltage, current and power also increased, confirming the theoretical relationship between rotational speed and induced EMF.

This project demonstrates the feasibility of renewable energy systems for small-scale electricity generation while reinforcing key concepts in electrical engineering and sustainable energy.

---

# 📂 Repository Structure

```text
Wind-Turbine-DC-Generator/
│
├── README.md
├── Project Report.pdf
├── Proteus Circuit/
├── Images/
│   ├── Construction
│   ├── Final Prototype
│   ├── Experimental Setup
│   └── Results
├── Schematics/
└── Results/
```

---

# 📷 Project Gallery

The repository includes:

- Construction process
- Final prototype
- Village model
- Circuit wiring
- Experimental setup
- Measurement process
- Proteus simulation
- Final report

---

# 📐 Theory

According to Faraday's Law of Electromagnetic Induction:

\[
E \propto N
\]

Where:

- **E** = Induced EMF
- **N** = Rotational speed

As the turbine rotates faster, the generator produces a higher output voltage.

Electrical power was calculated using:

\[
P = VI
\]

Where:

- **P** = Power (W)
- **V** = Voltage (V)
- **I** = Current (A)

---

# 🧠 Engineering Concepts

- Renewable Energy
- Wind Power
- DC Machines
- Electromagnetic Induction
- Ohm's Law
- Power Calculations
- Series & Parallel Circuits
- Electrical Measurements
- Sustainable Engineering

---

# 💡 Skills Demonstrated

- Electrical Circuit Design
- Renewable Energy Systems
- DC Generator Testing
- Circuit Construction
- Practical Wiring
- Soldering
- Electrical Measurements
- Experimental Analysis
- Proteus Simulation
- Technical Report Writing
- Engineering Problem Solving
- Troubleshooting

---

# 🚀 Future Improvements

- Add rechargeable battery storage.
- Integrate a charge controller.
- Use a permanent magnet generator.
- Install a voltage regulator.
- Monitor output using Arduino or ESP32.
- Implement IoT-based remote monitoring.
- Test using real outdoor wind conditions.

---

# 💻 Software

- Proteus Design Suite
- Microsoft Word
- Digital Multimeter

---

# 👨‍💻 Author

**Thato Maelane**

Bachelor of Engineering Technology (Electrical Engineering)

Tshwane University of Technology

---

## ⭐ If you found this project interesting, consider giving the repository a star!
