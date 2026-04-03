# 🧠 Filters_Localization_Python

> 📍 Python implementations of state estimation & localization filters as learnt in Probabilistic Robotics by S. Thrun. "This project is entirely to create an understanding for Kalman and Particle Filters (pardon for poor simulation)".

![Python](https://img.shields.io/badge/Python-3.14-blue?style=for-the-badge&logo=python)
![Status](https://img.shields.io/badge/Status-Experimental-yellow?style=for-the-badge)
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
![lkf_video-ezgif com-video-to-gif-converter](https://github.com/user-attachments/assets/874533fd-e667-4f3d-abb6-55e293625e5a)

📖 Learn more:
- https://en.wikipedia.org/wiki/Kalman_filter  
- https://www.kalmanfilter.net/

---

### 🔸 Extended Kalman Filter (EKF)
> Handles **non-linear systems via linearization**
> ![ekf_video](https://github.com/user-attachments/assets/6bdcdb0d-0c62-4637-9fb3-13c58fb63612)

📖 Learn more:
- https://en.wikipedia.org/wiki/Extended_Kalman_filter  

---

### 🔷 Unscented Kalman Filter (UKF)
> Uses **sigma points for better non-linear estimation**
> ![ukf_video](https://github.com/user-attachments/assets/473c375a-c93d-4cf9-89aa-157d6f7e97ef)


📖 Learn more:
- https://en.wikipedia.org/wiki/Unscented_Kalman_filter  

---

### 🔶 Particle Filter (PF)
> Uses **Monte Carlo sampling for complex distributions**
> ![pf_video](https://github.com/user-attachments/assets/2e05a7cf-8204-4ba2-8c49-01272d0f62f5)


📖 Learn more:
- https://en.wikipedia.org/wiki/Particle_filter  

---

---

## 🔬 Compare Filters

💡 Choosing the right filter depends on your system dynamics, noise, and compute constraints.

| Filter | Linear System | Nonlinear Handling | Computational Cost | Accuracy | Key Idea |
|--------|--------------|-------------------|--------------------|----------|----------|
|  LKF | ✅ Yes        | ❌ No              | 🟢 Low             | 🟢 High (linear only) | Exact Gaussian solution |
|  EKF | ❌ No         | ⚠️ Approximation   | 🟡 Medium          | 🟡 Medium | Linearization via Jacobian |
|  UKF | ❌ No         | ✅ Strong          | 🟡 Medium          | 🟢 High | Sigma points transform |
|  PF  | ❌ No         | ✅ Full            | 🔴 High            | 🟢 Very High | Monte Carlo sampling |

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
