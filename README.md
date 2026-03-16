# 🚗 Automotive Signaling System - Continental Summer Camp

## 🌟 Project Context
This project was developed during the **Continental Summer Camp**, an intensive practical internship focusing on automotive software engineering. Under the guidance of industry mentors, I designed and implemented a signaling control module that mimics real-vehicle logic.

## 📝 Project Overview
The system manages the external lighting logic of a vehicle, prioritizing safety and real-time responsiveness. It was built using **Arduino IDE (C++)** and focuses on efficient GPIO management and non-blocking programming patterns.

## 🚀 Key Features & Implementation
- **Prioritization Logic:** Hazard lights (emergency mode) take precedence over directional signals, a standard safety requirement in the automotive industry.
- **Timing Efficiency:** Implemented signal flashing frequencies using `millis()` instead of `delay()` to ensure the microcontroller can process other inputs (like emergency stops) simultaneously.
- **Debouncing Algorithms:** Integrated software debouncing for physical switches to ensure signal stability and prevent mechanical noise interference.

## 🛠️ Tech Stack
- **Hardware:** Arduino Microcontroller, LEDs, Tactile Switches.
- **Software:** C++, Arduino IDE.
- **Concepts:** Embedded Logic, State Machines, Automotive Standards.

---
*Developed by Angelo-Eduard Stanciu during the Continental Summer Camp 2024.*
