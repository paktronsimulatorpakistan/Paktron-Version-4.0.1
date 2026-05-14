# 🚀 PKTron 4.0.1 — Full-Stack Quantum Computing Framework

PKTron is a unified quantum computing simulation and research framework that integrates quantum algorithms, tensor networks, quantum machine learning, cryptography, hardware modeling, and HPC execution into a single Python ecosystem.

Developed by **CETQAP**.

---

## ⚙️ Key Features

### 🔬 Core Quantum Simulation Engine (13 Backends)

- Statevector simulation (exact up to ~28 qubits)
- Density Matrix simulation (noise + open systems)
- Matrix Product States (MPS) (50–100+ qubits)
- Adaptive MPS (dynamic entanglement scaling)
- PEPS (2D lattice systems)
- MERA (multi-scale entanglement systems)
- Clifford simulator (large stabilizer circuits)
- Pulse-level hardware simulation
- Quantum trajectory simulation
- Multi-GPU distributed statevector engine

---

## 🧠 Quantum Algorithms (50+ Implementations)

- Grover’s Search
- Shor’s Factoring Algorithm
- Quantum Fourier Transform (QFT)
- Quantum Phase Estimation (QPE)
- VQE / ADAPT-VQE
- QAOA (Max-Cut optimization)
- Quantum Annealing simulation
- Quantum Walks
- Amplitude Amplification
- Quantum Chemistry (H₂, BeH₂, Bravyi–Kitaev mapping)

---

## 🤖 Quantum Machine Learning

- Quantum Neural Networks (QNN)
- Quantum Support Vector Machines (QSVM)
- Quantum GANs
- Quantum CNNs
- Quantum Reinforcement Learning
- Quantum Autoencoders
- Quantum Federated Learning
- Quantum Transfer Learning

---

## 🔐 Quantum Cryptography & Security

- BB84, E91, MDI-QKD, DIQKD
- Quantum Secret Sharing
- Blind Quantum Computing
- Quantum Digital Signatures
- Post-Quantum Cryptography primitives

---

## 🧩 Error Correction & Mitigation

- Surface Code
- Steane [[7,1,3]] Code
- Bacon-Shor Code
- Color Codes
- Zero Noise Extrapolation (ZNE)
- Probabilistic Error Cancellation (PEC)
- Clifford Data Regression (CDR)
- Readout Error Mitigation
- MWPM-based logical error analysis

---

## ⚡ HPC, GPU & Distributed Runtime

- AVX-optimized C kernels
- GPU acceleration (CuPy backend)
- Multi-node distributed execution (MPI-style)
- DAG-based circuit scheduling
- Circuit caching & optimization
- Multi-backend runtime system

---

## 🏗️ Advanced Modules

- Tensor Networks (MPS, PEPS, MERA)
- Quantum Finance (portfolio optimization, Monte Carlo, risk models)
- Quantum Defense Systems (VRP, swarm optimization, scheduling)
- Quantum Chemistry workflows (active space, symmetry reduction)

---

## 🔄 Interoperability

- Qiskit support
- Cirq support
- PennyLane integration
- OpenQASM 2.0 / 3.0 support
- Quil export/import
- QPY binary serialization

---

## 📊 Benchmarking Suite

- Quantum Volume (QV)
- Randomized Benchmarking (RB)
- Cross Entropy Benchmarking (XEB)
- CLOPS throughput metrics
- State / Process / Gate tomography
- Layer fidelity estimation

---

## 🧪 Philosophy

PKTron is designed as a **full-stack quantum research ecosystem**, combining:

- Quantum physics simulation  
- Algorithm development  
- Quantum machine learning  
- Cryptography systems  
- Hardware modeling  
- High-performance computing  

---

## 📦 Installation

```bash
pip install pktron
