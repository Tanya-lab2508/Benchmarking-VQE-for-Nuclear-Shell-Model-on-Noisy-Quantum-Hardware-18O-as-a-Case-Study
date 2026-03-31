# Benchmarking VQE for Nuclear Shell Model on Noisy Quantum Hardware: ¹⁸O as a Case Study
This notebook benchmarks the Variational Quantum Eigensolver for computing the ground-state energy of ¹⁸O using the nuclear shell model with the USDB interaction. We systematically compare performance across three levels: Noiseless, Noisy and Error Mitigated. We also compare two qubit encodings, Jordan-Wigner and Gray Code, and study which is more noise-resilient on near-term hardware.

## Tools
- Qiskit
- NumPy
- SciPy
