# 🚀 Task 4 - Optimization Model | CODTECH Internship

This project solves a **real-world business problem** using **Linear Programming** and the **PuLP** optimization library in Python. The goal is to determine the optimal number of units for two products to maximize profit under labor and material constraints.

---

## 🧠 Problem Statement

A manufacturing company produces two products:

- **Product A** 🧱
  - Profit per unit: $20
  - Labor time: 2 hours
  - Material used: 3 kg

- **Product B** 🔩
  - Profit per unit: $30
  - Labor time: 3 hours
  - Material used: 4 kg

**Available resources:**
- Labor Time: 100 hours
- Material: 120 kg

### 🎯 Objective
Maximize total profit while ensuring the resource constraints are not violated.

---

## ✅ Solution Approach

The solution uses **Linear Programming (LP)** via the **PuLP** library.

- Decision Variables: Units of Product A and B to produce
- Constraints:
  - `2A + 3B ≤ 100` (Labor Time)
  - `3A + 4B ≤ 120` (Raw Material)
- Objective Function:
  - `Maximize: 20A + 30B`

---

## 📊 Outputs Provided

- ✅ **Optimal Production Plan**
- 💵 **Maximum Profit**
- 📉 **Resource Utilization**
- 🔎 **Sensitivity Analysis (Shadow Prices & Slacks)**
- 📈 **Visualization** of feasible region and optimal solution

---

## 📷 Visualization

A plot is generated showing the feasible region and optimal production point.

![Optimization Plot](production_optimization.png)

---

## 🛠️ Technologies Used

- Python 3
- [PuLP](https://coin-or.github.io/pulp/)
- Matplotlib
- NumPy
- JupyterLab

---
## 👨‍💻 Developed By

**Junaid Ahamed**  
_Data Science Intern @ CodTech_  
📅 Submitted: April 2025
