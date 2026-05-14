🚀 PKTron 4.0.1 — Full-Stack Quantum Computing Framework

PKTron is a unified quantum computing simulation and research framework designed to combine quantum algorithms, tensor networks, QML, cryptography, hardware modeling, and HPC execution into a single Python ecosystem.

Developed by CETQAP.

⚙️ Key Features
🔬 Core Quantum Simulation Engine (13 Backends)
Statevector (exact simulation up to ~28 qubits)
Density Matrix (noise + open quantum systems)
MPS / Adaptive MPS (50–100+ qubit scaling)
PEPS (2D lattice systems)
MERA (hierarchical entanglement models)
Clifford Simulator (massive stabilizer systems)
Pulse-level simulation (hardware-level modeling)
Multi-GPU distributed statevector engine
🧠 Quantum Algorithms (50+)
Grover’s Search
Shor’s Factoring
QFT / QPE
VQE / ADAPT-VQE
QAOA (Max-Cut & optimization)
Quantum Annealing
Quantum Walks & Amplitude Amplification
Quantum Chemistry (H₂, BeH₂, Bravyi–Kitaev)
🤖 Quantum Machine Learning
Quantum Neural Networks (QNN)
QSVM (quantum kernels)
Quantum GANs
Quantum CNNs
Quantum Reinforcement Learning
Quantum Autoencoders
Quantum Federated Learning
🔐 Quantum Cryptography & Security
BB84, E91, MDI-QKD, DIQKD
Quantum Secret Sharing
Blind Quantum Computing
Quantum Digital Signatures
Post-Quantum Cryptography primitives
🧩 Error Correction & Mitigation
Surface Code, Steane, Bacon-Shor, Color Codes
Zero Noise Extrapolation (ZNE)
Probabilistic Error Cancellation (PEC)
Clifford Data Regression (CDR)
Readout Error Mitigation
MWPM-based logical error analysis
⚡ HPC + GPU + Distributed Runtime
AVX-optimized C kernels
GPU acceleration (CuPy backend)
MPI-style distributed execution
DAG-based circuit scheduling
Circuit caching & fusion optimization
Multi-backend runtime system
🏗️ Advanced Modules
Tensor Networks (MPS, PEPS, MERA)
Quantum Finance (portfolio optimization, Monte Carlo, risk models)
Quantum Defense & Optimization (VRP, swarm optimization, scheduling)
Quantum Chemistry stack (active space, symmetry reductions)
🔄 Interoperability
Qiskit compatible
Cirq compatible
PennyLane integration
OpenQASM 2 / 3 support
Quil export/import
QPY binary serialization
📊 Benchmarking Suite
Quantum Volume (QV)
Randomized Benchmarking (RB)
Cross Entropy Benchmarking (XEB)
CLOPS throughput
Gate / state / process tomography
Layer fidelity estimation
🧪 Philosophy

PKTron is designed as a full-stack quantum research environment, not just a simulator.

It integrates:

physics simulation
algorithm design
quantum AI
cryptography
hardware modeling
HPC execution
📦 Installation
pip install pktron
🧠 Note

This framework is research-focused and modular. Performance depends on backend selection (CPU, GPU, distributed, or tensor-network mode).

⭐ Project Status

Active development (v4.0.1)
