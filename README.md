# Home Healthcare Routing and Scheduling Problem (HHCRSP) – Genetic Algorithm Implementation

This repository contains a **Java implementation of a Genetic Algorithm (GA)** to solve the **Home Healthcare Routing and Scheduling Problem (HHCRSP)**. The project focuses on optimizing caregiver routes and schedules to improve efficiency and service quality. The implementation features a **Best-Cost Route Crossover (BCRC)** and its variant **Best-Cost Route Crossover with Swap (BCRCS)**, developed as part of my MSc thesis research.

---

## 📂 Project Overview

The **Home Healthcare Routing and Scheduling Problem (HHCRSP)** is an NP-hard optimization problem that involves:

- Scheduling home healthcare caregivers efficiently.
- Assigning multiple patients to caregivers while considering skill compatibility.
- Optimizing travel routes to minimize time, cost and tardiness.
- Handling real-world constraints such as visit windows, and interdependent tasks.

This project implements a **Genetic Algorithm** to address these challenges, experimenting with crossover techniques and heuristics to produce high-quality solutions.

---

## ⚙️ Features

- **Genetic Algorithm Core**
  - Population initialization
  - Fitness evaluation based on total route cost
  - Selection strategies (e.g., tournament selection)
  - Elitism for preserving top solutions
  - Local search for refining solutions within neighborhoods

- **Crossover Operators**
  - **BCRC (Best-Cost Route Crossover):** Selects the best-cost route from parents and reinserts patients optimally.
  - **BCRCS (BCRC with Swap):** Extends BCRC by swapping patients within routes to further reduce costs.

- **Configurable Parameters**
  - Population size
  - Number of generations
  - Crossover rates
  - Local Search rates
  - Selection type and elitism rate

- **Experimental Framework**
  - Run multiple instances with configurable seeds
  - Collect statistics for performance analysis
  - Supports reproducibility for thesis experiments

---

## 🛠️ Requirements

- **Java 11 or higher**
- Compatible with Windows, Linux, and macOS
- Optional: IDE such as Eclipse, IntelliJ, or VS Code for easier development

---

## 📚 References

- Mankowska, D.S., Meisel, F., & Bierwirth, C. (2014). *The home health care routing and scheduling problem with interdependent services*. Health Care Management Science, 17(1), 15–30.

