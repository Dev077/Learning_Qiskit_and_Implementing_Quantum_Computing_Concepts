# Quantum Computing with Qiskit

An exploration of quantum computing fundamentals through hands-on implementation using IBM's Qiskit framework. This project demonstrates key quantum computing concepts including superposition, entanglement, quantum arithmetic, and quantum algorithms.

## Overview

This repository contains Python implementations of various quantum circuits and algorithms, progressing from basic single-qubit operations to complex multi-qubit quantum algorithms. Each module explores different aspects of quantum computing theory through practical simulation and visualization.

## Technologies Used

- **Qiskit** - IBM's open-source quantum computing framework
- **Python** - Primary programming language
- **AerSimulator** - High-performance quantum circuit simulator
- **NumPy** - Numerical computations
- **Matplotlib** - Visualization of quantum states and measurement outcomes

## Projects

### 1. Quantum Circuit Development & Simulation

Foundational work with quantum circuits implementing basic quantum operations:

- Designed and implemented quantum circuits with single and multi-qubit operations (X, H, RY, Phase gates)
- Simulated quantum systems using AerSimulator with up to 10,000 shots for statistical analysis
- Visualized quantum states and measurement results through histograms and Bloch sphere representations

**Key Concepts:** Quantum gates, superposition, measurement, quantum state visualization

### 2. Quantum Entanglement & Bell States

Exploration of quantum entanglement phenomena through Bell state construction:

- Created Bell state circuits demonstrating quantum entanglement using Hadamard and CNOT gates
- Analyzed quantum superposition states across 2-qubit systems
- Measured and validated correlation between entangled qubits through statistical analysis

**Key Concepts:** Quantum entanglement, Bell states, CNOT gates, quantum correlation

### 3. Quantum Arithmetic Circuits

Implementation of quantum computing for arithmetic operations:

- Developed quantum adder circuits using CNOT and Toffoli (CCX) gates for binary addition on 4-qubit systems
- Implemented and tested quantum XOR operations for all input combinations (00, 01, 10, 11)
- Investigated superposition-based quantum arithmetic by applying Hadamard gates to input qubits

**Key Concepts:** Quantum logic gates, Toffoli gates, quantum arithmetic, computational basis states

### 4. Quantum Fourier Transform (QFT)

Advanced quantum algorithm implementation for frequency domain analysis:

- Built 2-qubit Quantum Fourier Transform circuits using controlled-phase rotations and SWAP gates
- Visualized quantum state transformations on the Bloch sphere to validate circuit behavior
- Analyzed statevector outputs to verify correct frequency domain transformations

**Key Concepts:** Quantum Fourier Transform, controlled-phase gates, quantum phase estimation, frequency domain

## Learning Outcomes

Through these implementations, this project demonstrates understanding of:

- Quantum circuit design and optimization
- Quantum gate operations and their matrix representations
- Quantum measurement and the collapse of superposition
- Quantum entanglement and non-local correlations
- Quantum algorithms and their computational advantages
- Visualization and analysis of quantum states
