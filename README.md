# Single-Qubit Gates with Qiskit

A beginner quantum computing project built using Python and Qiskit.

## Project Objective

The goal of this project is to understand how a single qubit behaves when a quantum gate is applied and how measurement produces probabilistic results.

## What This Project Does
This notebook:
- Creates a quantum circuit with one qubit and one classical bit
- Starts the qubit in the default state `|0⟩`
- Applies a Hadamard gate to the qubit
- Creates a superposition state
- Measures the qubit 1,000 times using the Qiskit Aer Simulator
- Displays the measurement counts and a bar graph

## Quantum Concept
The qubit initially starts in the state:|0⟩
After applying the Hadamard gate, its state becomes:
H|0⟩ = (|0⟩ + |1⟩)/(2)^(1/2)
This is called **superposition**. Before measurement, the qubit has equal probability amplitudes for `|0⟩` and `|1⟩`.
When measured many times, the expected result is approximately:
- `0`: 50%
- `1`: 50%
The exact number may be different in every run because quantum measurement is probabilistic.

## Tools Used
- Python
- Qiskit
- Qiskit Aer Simulator
- Matplotlib
- Jupyter Notebook

## Requirements

Install the required libraries before running the notebook:

```python !pip install qiskit qiskit-aer matplotlib```

## How to Run
1. Open `single_qubit_gates.ipynb` in Jupyter Notebook or JupyterLab.
2. Run the installation cell if the required libraries are not installed.
3. Run all notebook cells.
4. Observe the quantum circuit, measurement counts, and bar graph.

## Key Concepts Learned
- Qubit
- Computational basis states `|0⟩` and `|1⟩`
- Quantum gates
- Hadamard gate
- Superposition
- Measurement
- Probability amplitudes
- Qiskit circuit simulation

## Future Improvements

- Add Pauli-X and Pauli-Z gate demonstrations
- Compare different quantum gates
- Visualize qubit states on the Bloch sphere
- Run the circuit on real quantum hardware
