# 🧠 Filters_Localization_Python

> 📍 Python implementations of state estimation & localization filters as learnt in Probabilistic Robotics by S. Thrun

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python)
![Status](https://img.shields.io/badge/Status-Learning%20%2F%20Experimental-yellow?style=for-the-badge)
![Domain](https://img.shields.io/badge/Domain-Robotics%20%7C%20Estimation-orange?style=for-the-badge)

---

## 🌐 Overview

This repository contains **clean Python implementations** of fundamental probabilistic filters used in:

- 🤖 Robotics  
- 🚗 Autonomous systems  
- 📡 Sensor fusion  
- 📍 Localization  

---

## 🧩 Implemented Filters

### 🔹 Linear Kalman Filter (LKF)
> Optimal for **linear systems with Gaussian noise**

📖 Learn more:
- https://en.wikipedia.org/wiki/Kalman_filter  
- https://www.kalmanfilter.net/

---

### 🔸 Extended Kalman Filter (EKF)
> Handles **non-linear systems via linearization**

📖 Learn more:
- https://en.wikipedia.org/wiki/Extended_Kalman_filter  

---

### 🔷 Unscented Kalman Filter (UKF)
> Uses **sigma points for better non-linear estimation**

📖 Learn more:
- https://en.wikipedia.org/wiki/Unscented_Kalman_filter  

---

### 🔶 Particle Filter (PF)
> Uses **Monte Carlo sampling for complex distributions**

📖 Learn more:
- https://en.wikipedia.org/wiki/Particle_filter  

---

---

## 🔬 Compare Filters

💡 Choosing the right filter depends on your system dynamics, noise, and compute constraints.

| Filter | Linear System | Nonlinear Handling | Computational Cost | Accuracy | Key Idea |
|--------|--------------|-------------------|--------------------|----------|----------|
| 🔹 LKF | ✅ Yes        | ❌ No              | 🟢 Low             | 🟢 High (linear only) | Exact Gaussian solution |
| 🔸 EKF | ❌ No         | ⚠️ Approximation   | 🟡 Medium          | 🟡 Medium | Linearization via Jacobian |
| 🔷 UKF | ❌ No         | ✅ Strong          | 🟡 Medium          | 🟢 High | Sigma points transform |
| 🔶 PF  | ❌ No         | ✅ Full            | 🔴 High            | 🟢 Very High | Monte Carlo sampling |

---

## 📚 Reference & Learning Resources

📘 This project is inspired by:

### 📖 Probabilistic Robotics — Sebastian Thrun

- 🔗 https://mitpress.mit.edu/9780262201629/probabilistic-robotics/  
- 🔗 https://www.probabilistic-robotics.org/  

💡 *Highly recommended if you want deep intuition behind all filters implemented here.*

---

## 🎯 Key Concepts

<details>
<summary>📘 Click to explore core ideas</summary>

- 📊 State estimation  
- 📉 Noise modeling (Gaussian / Non-Gaussian)  
- 🔁 Prediction & update cycle  
- 🎲 Probabilistic inference  
- 📡 Sensor fusion  

</details>

---

## 📂 Project Structure

<details>
<summary>📁 Expand structure</summary>
