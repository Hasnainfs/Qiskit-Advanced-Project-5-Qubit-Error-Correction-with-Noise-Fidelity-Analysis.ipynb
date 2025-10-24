# ⚛️ 5-Qubit Error Correction with Noise & Fidelity Analysis

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1yWLe2X5ff1Jjqw1hMdBTBBibTdIIVKU5?usp=sharing)

This repository demonstrates **3-qubit and 5-qubit quantum error correction (QEC)** implemented in **Qiskit**, including simulations under noise and execution on **IBM Quantum hardware**, with fidelity analysis.

---

## 🚀 Run the Notebook on Google Colab
🔗 **[Open in Google Colab](https://colab.research.google.com/drive/1yWLe2X5ff1Jjqw1hMdBTBBibTdIIVKU5?usp=sharing)**

---

## 🧠 Project Overview
**Title:** 5-Qubit Error Correction with Noise & Fidelity Analysis  
**Objective:** Implement a 5-qubit quantum error correction code, simulate depolarizing noise, run on IBM Quantum hardware, and evaluate fidelity and logical error rates.

---

## 📦 Installation
Install dependencies in Colab or Jupyter:

```bash
%pip install --upgrade qiskit qiskit-ibm-runtime matplotlib numpy
from qiskit import QuantumCircuit, transpile
from qiskit_aer import AerSimulator
from qiskit_ibm_runtime import QiskitRuntimeService, SamplerV2 as Sampler
from qiskit.quantum_info.analysis import hellinger_fidelity
import matplotlib.pyplot as plt
import numpy as np
Connected to real backend: ibm_brisbane
Running job on hardware. This may take some time.
Job ID: d3ovb25q5lhs73bb5hq0
{'00000': 748, '00110': 326, '01110': 44, '00101': 13, '00111': 452, '00100': 22,
 '10110': 12, '01000': 70, '01111': 39, '10111': 14, '10000': 22, '00001': 103,
 '01001': 20, '00011': 25, '00010': 24, '11101': 1, '11010': 1, '01011': 10,
 '01010': 25, '01101': 10, '01100': 7, '10101': 9, '10010': 7, '10100': 10,
 '10011': 7, '11110': 1, '11100': 2, '10001': 14, '11011': 4, '11111': 1,
 '11001': 2, '11000': 3}
{'00111': 141, '00000': 875, '00001': 150, '00110': 882}
