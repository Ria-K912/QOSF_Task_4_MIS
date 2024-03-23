# Quantum Algorithms for MIS Solver

This repository contains a quantum computing-based solution to the Maximum Independent Set (MIS) problem. The solution utilizes two different quantum computing approaches: the Quantum Approximate Optimization Algorithm (QAOA) implemented via the Classiq framework and a simulation of the quantum adiabatic algorithm based on analog quantum computing using DWave Ocean SDK.

## Features

- **Graph Generation**: Creates random graphs with predefined node counts and edge probabilities.
- **MIS Problem Formulation**: Defines the MIS problem using binary optimization models in Pyomo.
- **QAOA Implementation**: Employs the QAOA via Classiq for quantum optimization.
- **Quantum Adiabatic Algorithm**: Simulates the adiabatic process for finding MIS using DWave Ocean SDK.
- **Visualization**: NetworkX and Matplotlib are used for visual representation of graphs and solutions.
- **Convergence Analysis**: Plots energy convergence to assess optimization performance.

## Prerequisites

To run the code, you need:
- Python 3.8 or newer
- NetworkX for graph-related operations
- Pyomo for creating optimization models
- Matplotlib for generating plots
- Classiq SDK for building and executing gated qaoa
- DWave SDK for building and executing quantum adiabatic algorithm based on analog quantum computing

## Install the required Python dependencies:
```bash
pip install networkx pyomo matplotlib classiq dwave-ocean-sdk
```


## Setup

Clone this repository:
```bash
git clone https://github.com/Ria-K912/QOSF_Task_4_MIS.git
```




