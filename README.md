# 🔄 Convolutional Code Simulation & Performance Analysis

This project implements and analyzes **convolutional coding** using **MATLAB**, focusing on **hard** and **soft decision Viterbi decoding**. It explores how different constraint lengths and generator polynomials affect Bit Error Rate (BER), Frame Error Rate (FER), and Frame Success Rate under varying noise levels.

---

## 📁 Repository Contents


---

## 🧠 What You’ll Learn

- How convolutional codes work and are implemented
- Differences between hard and soft decision decoding
- How to calculate and simulate:
  - **Bit Error Rate (BER)**
  - **Frame Error Rate (FER)**
  - **Frame Success Rate**
- How decoding performance changes with SNR

---

## 📘 Theory (📄 Report.pdf)

Includes detailed derivations of:

- Transfer function of convolutional codes  
- Minimum free distance calculation  
- Upper bounds on BER using union bound and Q-function  
- Comparison between hard and soft decoding performance  
- Error analysis on AWGN and BSC channels  

---

## ⚙️ Simulation Setup

Tested Cases:
- **Case 1**:  
  - K = 3  
  - Generators: (101), (111)
- **Case 2**:  
  - K = 4  
  - Generators: (1101), (1111), (1001)
- **Case 3**:  
  - K = 6  
  - Generators: (101111), (111001), (110101)

Channel:  
- **AWGN** with **BPSK modulation**

SNR Range:  
- **0 to 10 dB** (in 0.5 dB steps)

---
