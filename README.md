# Phase Retrieval and Matrix Completion through projection-based algorithms

## Overview
This repository contains the code and numerical experiments from the thesis "Phase Retrieval and Matrix Completion through projection-based algorithms". The project investigates two fundamental problems in signal processing:

1. **Phase Retrieval**: Recovering the global phase vector from Fourier magnitude data.
2. **Matrix Completion**: Reconstructing low-rank matrices from partial data.

The research systematically compares the performance of projection-based algorithms under varying conditions, highlighting trade-offs in reliability, computational efficiency, and scalability.

---

## Features
- Implementation of projection-based algorithms for phase retrieval and matrix completion.
- Evaluation of algorithmic performance under various scenarios:
  - **Random Phase Retrieval**
  - **Crystallographic Phase Retrieval**
  - **Matrix Completion with Low-Rank Constraints**
- Analysis of robustness to noise and effects of missing data.
- Visualization of convergence behavior and performance metrics.

---

## Installation

Clone the repository:
```bash
$ git clone https://github.com/YoavHarlap/Phase_retrieval_and_matrix_completion_through_projection-based_algorithms.git
$ cd Phase_retrieval_and_matrix_completion_through_projection-based_algorithms
```

Install required dependencies:
```bash
$ pip install -r requirements.txt
```

---
## Repository Structure
- **phase_retrieval.py**: Implements phase retrieval algorithms and experiments.
- **matrix_completion.py**: Implements matrix completion algorithms and experiments.
- **visualize_results.py**: Contains scripts to visualize and analyze results.
- **data/**: Contains example datasets for experiments.
- **results/**: Stores output from experiments, including metrics and plots.
- **requirements.txt**: List of dependencies.

---

## Results
Detailed numerical results and analysis are available in the **results/** folder. These results provide actionable insights into selecting algorithms for specific problems and conditions.

---

