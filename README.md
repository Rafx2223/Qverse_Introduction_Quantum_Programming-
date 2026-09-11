# QVerse — Introduction to Quantum Computing & Programming

This folder contains the 16 student notebooks for the QVerse beginner course.

## Recommended environment

```bash
python3 -m venv .venv
source .venv/bin/activate
python -m pip install --upgrade pip
python -m pip install "qiskit[visualization]>=2.5" matplotlib numpy jupyter
```

Week 14 optionally uses Qiskit Aer:

```bash
python -m pip install qiskit-aer
```

## Course sequence

01. Orientation and first Qiskit circuits
02. Minimum quantum mathematics
03. One-qubit states and gates
04. Phase and interference
05. Multiple qubits and bit ordering
06. Entanglement and Bell states
07. Gate toolbox and rotations
08. Measurement, shots, and statistics
09. Teleportation and superdense coding
10. Oracles and Deutsch–Jozsa
11. Grover and amplitude amplification
12. Quantum Fourier Transform
13. Hybrid variational workflows
14. Noise, transpilation, and hardware
15. Capstone build
16. Capstone validation and presentation

The notebooks are designed to be standalone and self-paced. Guided examples are complete; student exercises are marked TODO.
