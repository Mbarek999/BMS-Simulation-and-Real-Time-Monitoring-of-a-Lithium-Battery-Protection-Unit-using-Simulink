# 🔋 BMS: Simulation and Real-Time Monitoring of a Lithium Battery Protection Unit using Simulink

This project presents a **Battery Management System (BMS)** designed for the **simulation and real-time monitoring** of a lithium battery protection unit. Built using **Simulink** and **MATLAB**, the system ensures battery safety, longevity, and optimal performance through intelligent software-based control and visualization.

---

## 📌 Overview

The BMS is developed to:

- **Simulate** critical lithium battery parameters such as **voltage**, **current**, and **state-of-charge (SoC)**.
- **Monitor and control** the battery’s operating conditions in real time.
- **Protect** the battery against **overcharging** and **deep discharging**.
- **Implement control logic** for safe operation using **Stateflow**.
- **Visualize data** for analysis and debugging using MATLAB tools.

---

## 🛠 Tools & Technologies

- MATLAB & Simulink
- Battery Models
- Stateflow
- Real-Time Data Visualization Tools

---

## ⚙️ Features

- ✅ Simulates lithium battery voltage and current behavior under various loads and charging cycles.
- ✅ Stateflow-based protection logic for:
  - Overvoltage detection
  - Undervoltage protection
  - Current limit monitoring
- ✅ Real-time monitoring interface using scopes and dashboards
- ✅ Battery health visualization using MATLAB plots
- ✅ Customizable thresholds for protection parameters

---

## 🧠 System Architecture

```mermaid
graph TD
    A[Battery Model] --> B[Simulink Control Logic]
    B --> C{Stateflow Protection Unit}
    C --> D[Overvoltage Handler]
    C --> E[Undervoltage Handler]
    B --> F[Current Monitoring]
    F --> C
    C --> G[Visualization Dashboard]
