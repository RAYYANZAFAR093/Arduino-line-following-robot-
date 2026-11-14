# Arduino-line-following-robot-
An Arduino-based line follower robot prototype built with an L911OS Dual- channel H-bridge motor driver. Early-stage hardware build documenting prototyping lessons and future PID control upgrades

# 🤖 Arduino Line Follower Robot (Prototype v1)

An entry-level 4WD/2WD Line Follower Robot built using an **Arduino Uno** and an **L9110S motor driver**. This repository documents the first iteration of my mobile robotics journey, focusing on hardware assembly, basic sensor calibration, and iterative prototyping.

---

## 🛠️ Hardware Stack & Components
* **Microcontroller:** Arduino Uno (DIP / R3)
* **Motor Driver:** L9110S Dual-Channel H-Bridge Motor Driver
* **Actuators:** BO Gear Motors
* **Sensing:** IR Sensor Array / IR Obstacle Avoidance Modules
* **Power Supply:** 7.4V 18650 Li-ion Battery Pack
* **Chassis & Assembly:** Custom prototype chassis, hot glue, jumper wires, and electrical tape

---

## 🚧 Current Status & Prototype Challenges (v1)
This is an experimental proof-of-concept build. While putting this together, I encountered a few classic prototyping hurdles:
* **Short Circuits:** Dealt with a few accidental short circuits due to tight wiring on breadboards and loose power connections—a great lesson in double-checking pinouts and insulating connections!
* **Basic Control Logic:** Currently running on simple digital threshold-based steering rather than smooth proportional control, which leads to some line oscillation on sharp turns.

---

## 🚀 Future Roadmap & Next Steps
* [ ] **Upgrade to PID Control:** Transitioning the steering logic from basic threshold logic to a **PID (Proportional-Integral-Derivative) algorithm** for much smoother, higher-speed line tracking.
* [ ] **PCB Migration:** Moving away from breadboard wiring to a cleaner soldered perfboard or custom PCB layout to eliminate loose wiring and short-circuit risks.
* [ ] **Power Optimization:** Refining the battery distribution and adding decoupling capacitors to isolate motor noise from the microcontroller.

---

## 📂 Repository Structure
```text
├── code/
│   └── line_follower_basic.ino   # Current baseline threshold navigation code
└── README.md
