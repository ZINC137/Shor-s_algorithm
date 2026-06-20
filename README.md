# Shor's Algorithm using Qiskit

Implementation of **Shor's Algorithm** in Qiskit to factor **N = 15** using Quantum Phase Estimation (QPE) and the Quantum Fourier Transform (QFT).

This is my first Quantum Computing project, completed as part of the QC101 Quantum Computing Course offered at IIT Guwahati. The project provided hands-on experience with quantum circuits, QFT, QPE, Shor's Algorithm, and execution on real IBM Quantum hardware.

## Results

* Number to factor: **15**
* Chosen base: **a = 7**
* Period found: **r = 4**
* Factors obtained: **3 × 5**

## Features

* Modular exponentiation oracle
* Inverse Quantum Fourier Transform (QFT†)
* Quantum Phase Estimation
* Classical post-processing using GCD
* Execution on IBM Quantum hardware (`ibm_kingston`)

## Technologies

* Python
* Qiskit
* Qiskit IBM Runtime
* IBM Quantum Hardware

## Outcome

Successfully demonstrated Shor's Algorithm on both a simulator and real IBM Quantum hardware, recovering the correct period and factoring:

**15 = 3 × 5**

## Author

**Smruti Ranjan Ghosh**

