# 🌟 Convolution Codes Simulation

![Matlab](https://img.shields.io/badge/MATLAB-Supported-blue.svg) 
![Version](https://img.shields.io/badge/version-1.0-blue.svg)

---

## 🔗 Table of Contents

- [📌 Project Overview](#-project-overview)
- [✨ Features](#-features)
- [🚀 Getting Started](#-getting-started)
- [🎯 Usage](#-usage)
- [📊 Results](#-results)
- [🤝 Contributing](#-contributing)

---

## 📌 Project Overview

This project explores **Convolutional Codes** and their effectiveness in error correction for digital communication. The workflow includes:

✅ Encoding message bits using **convolutional codes**  
✅ Modulation via **BPSK**  
✅ Simulation of **AWGN Channel**  
✅ Decoding using **Viterbi Algorithm (Hard & Soft Decision)**  
✅ Performance evaluation through **BER curves**

---

## ✨ Features

🚀 **Viterbi Hard & Soft Decision Decoding**  
📡 **Realistic SNR Adjustments**  
📈 **Graphical Performance Analysis**  
📂 **Structured MATLAB Implementation**  
🔁 **Reproducible Simulations**

---

## 🚀 Getting Started

### 🔧 Installation

1️⃣ **Clone the Repository**
```sh
git clone https://github.com/your-username/convolution-codes.git
cd convolution-codes
```
2️⃣ **Open MATLAB** and navigate to the project folder.
3️⃣ **Run the main script**
```matlab
simulation
```

---

## 🎯 Usage

Modify parameters inside `simulation.m` to customize your tests:
```matlab
snr_range = 0:0.5:10;  % Adjust SNR range
rate = [1/2, 1/3];     % Code rates
K = [3, 4, 6];         % Constraint lengths
```
Run `simulation.m` and check the results in the `results/` directory.

---

## 📊 Results

Generated graphs showcase **BER vs SNR** for different configurations. Example:

![BER Curve](https://via.placeholder.com/600x300?text=BER+vs+SNR)

---

## 🤝 Contributing

🔹 **Fork the repository**  
🔹 **Create a new branch** (`git checkout -b feature-name`)  
🔹 **Commit changes** (`git commit -m 'Added feature'`)  
🔹 **Push branch** (`git push origin feature-name`)  
🔹 **Create a Pull Request** 🎉


