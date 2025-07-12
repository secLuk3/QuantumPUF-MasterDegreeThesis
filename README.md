# Quantum Physical Unclonable Functions (QPUF)

This repository contains the code and documentation for the Master's Thesis project titled **"Progettazione di circuiti per l’implementazione di Quantum Physical Unclonable Functions (QPUF)"** by Luca Boffa at the University of Salerno.

## 🎯 Project Overview

Quantum Physical Unclonable Functions (QPUFs) leverage the intrinsic randomness and noise of quantum hardware to generate unique, unclonable responses to challenges. This work investigates the design, implementation, and evaluation of various QPUF circuits, focusing on security, randomness, stability, and uniqueness.

## 🧪 Key Features

- 🧠 **Custom QPUF Circuits**: Eight unique architectures named after planets (e.g., Earth, Mars, Venus) with distinct logic and entanglement strategies.
- 🔬 **Real Hardware Testing**: Circuits tested on IBM Quantum devices like `ibmq_kyiv`, `ibmq_sherbrooke`, and `ibmq_brisbane`.
- 📊 **Performance Metrics**:
  - *Instability*
  - *Randomness*
  - *Uniqueness*
- 🔁 **Challenge-Response Protocol**: Using parameterized quantum gates as challenges; responses derived from measurement histograms.
- 🔧 **Qiskit Implementation**: Modular Jupyter notebooks for easy configuration and testing across different devices.

## 🧰 Technologies Used

- [Qiskit](https://qiskit.org/)
- IBM Quantum Cloud
- Python

## 📁 Repository Structure
/ # Experiment scripts and testing setup
/result/backend/real # Collected response data from real machines (CSV files)
/result/backend/fake # Collected response data from simulator machines (CSV files)
/result/circuits/ # QPUF circuit definitions (Qiskit)
README.md # Project documentation

## 📄 Thesis PDF

For detailed methodology and analysis, see the full thesis (available in the `docs/` or main directory as `Tesi_Magistrale_Luca_Boffa_Beta_v1_2_pdfA.pdf`).

