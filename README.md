# 🚀 PKTron — Full Quantum Computing Framework (v4.0.1)

PKTron is a large-scale quantum computing simulation and research framework integrating quantum circuits, algorithms, machine learning, cryptography, tensor networks, HPC acceleration, and hardware modeling into a unified architecture.

---

# 🔬 Core Module (pktron.core) — 50+ Classes

## 🧠 Simulators

| Class | Description |
|------|------------|
| QuantumCircuit | 23-gate circuit builder; supports standard + custom unitaries |
| StatevectorSimulator | Exact simulation up to ~28 qubits |
| DensityMatrixSimulator | Mixed states, Kraus channels, Lindblad noise |
| MPSSimulator | Matrix Product States (50–100+ qubits) |
| AdaptiveMPSSimulator | Auto bond-dimension MPS |
| PEPSimulator | 2D Projected Entangled Pair States |
| MERASimulator | Multi-scale Entanglement Renormalisation Ansatz |
| TensorNetworkSimulator | General tensor contraction engine |
| CliffordSimulator | Stabilizer tableau (millions of qubits) |
| PulseLevelSimulator | Time-domain Lindblad master equation |
| QuantumTrajectorySimulator | Quantum trajectory unraveling |
| MultiGPUSimulator | Distributed GPU statevector (CuPy) |

---

## ⚛️ Gate Set (23 Native Gates)

H, X, Y, Z, S, T, Rx, Ry, Rz, CNOT, CZ, SWAP, iSWAP, CCX, CSWAP, CRz, Rzz, Rxx, Ryy, DCX, ECR, U3

Plus:
- Parametric gates  
- Barrier  
- Mid-circuit measurement  
- Conditional gates  
- Custom unitary injection  

---

## 🧮 Quantum Algorithms

| Class | Algorithm |
|------|----------|
| GroverSearch | Amplitude amplification |
| Shor | QPE-based factoring |
| VQE | Variational Quantum Eigensolver |
| QAOA | Max-Cut optimization |
| HHLAlgorithm | Linear system solver |
| QuantumPhaseEstimation | IQFT-based QPE |
| SimonsAlgorithm | Hidden subgroup (GF2) |
| DeutschJozsa | Oracle algorithm |
| QuantumFourierTransform | QFT |
| AmplitudeAmplification | Generalized AA |
| QuantumCounting | QPE-based counting |
| QuantumWalk | Discrete quantum walk |
| QuantumAnnealing | Annealing simulation |
| QuantumChemistry | H₂ / BeH₂ mapping |

---

## 🤖 QML & Optimization

Quantum machine learning stack:

- QuantumNeuralNetwork  
- QSVM  
- QuantumGAN  
- QuantumAutoencoder  
- QuantumCNN  
- QuantumBoltzmannMachine  
- QuantumFederatedLearning  
- QuantumReinforcementLearning  
- QuantumTransferLearning  

---

## 🔐 Cryptography & QKD

| Class | Description |
|------|------------|
| BB84Protocol | QKD with noise + QBER + eavesdropping |
| PostQuantumCrypto | Lattice/hash-based cryptography |

---

## 🧩 Error Mitigation

- ZeroNoiseExtrapolation (Richardson)
- ProbabilisticErrorCancellation (PEC)
- CliffordDataRegression (CDR)
- ReadoutErrorMitigation
- DynamicalDecoupling

---

## 🧠 Error Correction

| Code | Description |
|------|------------|
| Steane7QEC | [[7,1,3]] code |
| SurfaceCode | Rotated surface code |
| SurfaceCodeDistance | MWPM logical error rate |
| BaconShorCode | Subsystem code |
| ColorCode | Topological code |
| RepetitionCode | Classical analogue |

---

## ⚙️ Hardware & Transpilation

- SABRERouter (qubit routing)
- HardwareBackend (noise-aware execution)
- DRAGPulse (optimal control)
- CrossResonancePulse

---

## 📊 Benchmarking

- Quantum Volume (QV)
- Randomized Benchmarking (RB)
- Cross Entropy Benchmarking (XEB)
- CLOPS throughput metrics

---

# 🧩 Specialised Modules (25+)

| Module | Key Class | Description |
|------|-----------|------------|
| matchgate_sim | MatchgateSimulator | Exact fermionic simulation |
| dmrg | DMRGSolver | Heisenberg / Ising ground states |
| fermionic_gaussian | FermionicGaussianSimulator | Gaussian fermionic states |
| qkd_pipeline | QKDPipeline | BB84 → DIQKD pipeline |
| barren_plateau | BarrenPlateauAnalyzer | Gradient landscape analysis |
| noise_aware_compile | NoiseAwareCompiler | Noise-aware compilation |
| qsvt | QSVT | Singular value transformation |
| circuit_debugger | QuantumCircuitDebugger | Step-by-step execution |
| gradients | ParameterShiftGradient | Quantum gradients |
| pauli | PauliSum | Sparse Pauli algebra |
| decompose | KAK / Euler decomposition |
| interop | InteropConverter | Qiskit/Cirq/PennyLane/QASM3 |
| advanced_qml | QuantumKernelTrainer | Advanced QML |
| advanced_mitigation | SymmetryVerification | Mitigation methods |
| advanced_crypto | QuantumSecretSharing | Quantum crypto |
| advanced_algorithms | QuantumMetropolis | Advanced algorithms |
| new_algorithms | QuantumWalkSearch | Next-gen algorithms |
| finance | QuantumPortfolioOptimizer | Finance models |
| defense | QuantumVRP | Logistics & defense |

---

# ⚙️ Advanced Module (pktron.advanced)

- UCCSDSolver (Unitary Coupled Cluster)
- ADAPTVQESolver
- VirtualDistillation
- OpenQASM3 export/import
- JAXOptimizer
- SurfaceCodeDistance
- AdaptiveMPSSimulator

---

# 🚀 HPC Subsystem (8 Subpackages)

## Kernels & Runtime

- AVX-512 / AVX2 / SSE optimized kernels
- OpenMP parallel execution
- Gate fusion + sampling kernels

## Scheduler & Runtime

- DAG-based scheduling
- Clifford detection engine
- Multi-backend execution system

## GPU & Distributed

- CuPy GPU backend
- MPI-style distributed runtime
- Multi-GPU orchestration

## Sparse & Cache

- Sparse Hamiltonians (Ising, Heisenberg)
- Circuit caching system

---

# 🏗 Modular Architecture (v4.0.1)

- BackendRegistry
- QuantumIR compiler
- TaskGraphScheduler
- TensorNetwork engine
- GPU memory pool
- Visualization tools

---

# 🔧 Hardware & Noise Modules

- Noise models (Depolarizing, Amplitude damping, Crosstalk)
- Gate scheduling system
- Drift simulation engine
- Dynamic circuits (feed-forward logic)
- Virtual devices
- Hardware execution reports

---

# 🛠 Utility Modules

- PKTronConfig (config system)
- QuantumStateValidator
- PerformanceMonitor

---

# 🔬 Chemistry Expansion (14 Classes)

- Molecule
- ElectronicStructureProblem
- HartreeFockInitialPoint
- ActiveSpaceTransformer
- FreezeCoreTransformer
- Z2Symmetries
- ParityMapper
- BravyiKitaev mapping
- kUpCCGSD
- PUCCD / SUCCD
- qEOM
- SSVQE

Molecules:
H₂, N₂, CH₄, CO₂, NH₃, C₂H₄

---

# 🔄 Interoperability (9 Classes)

- QASM2Codec
- QASM3Parser
- QuilExporter
- QiskitImporter
- CirqImporter
- PennyLaneImporter
- IonQExporter
- BraketExporter
- QPYCodec

---

# 🧮 Pauli Framework (7+ Functions)

- Pauli (symplectic)
- SparsePauliOp
- PauliGrouper
- commutator / anti-commutator
- commuting group decomposition

---

# 🔁 Circuit Construction (13 Classes)

- Parameter / ParameterVector
- QuantumRegister / ClassicalRegister
- DAGCircuit / DAGNode
- Control flow (If, While, For, Switch)
- Circuit transformations (.compose, .inverse, .tensor)

---

# 🔬 Benchmarking Suite

- StandardRB
- InterleavedRB
- MirrorRB
- XEB (cross entropy)
- CLOPS
- StateTomography
- ProcessTomography
- GateTomography
- LayerFidelityEstimator

---

# 🩹 Physics & Algorithm Fixes (15+)

- Correct GHZ uniform distribution
- Fixed QPE phase estimation
- Simon’s algorithm correction
- Deutsch-Jozsa oracle fix
- VQE normalization guarantees
- QAOA energy correction
- XEB formula correction
- Surface code MWPM decoding
- BB84 QBER realism improvements
- DMRG convergence stability
- GRAPE optimization fixes

---

# 📦 Summary

PKTron integrates:

- Quantum simulation (statevector → tensor networks)
- Quantum algorithms (classical + variational)
- Quantum machine learning
- Cryptography & QKD
- Error correction & mitigation
- HPC + GPU + distributed runtime
- Chemistry simulation
- Finance & defense optimization
- Full interoperability ecosystem
