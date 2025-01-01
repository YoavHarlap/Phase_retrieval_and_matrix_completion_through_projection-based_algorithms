# Phase_retrieval_and_matrix_completion_through_projection-based_algorithms
# Phase Retrieval and Matrix Completion through projection-based algorithms

## Overview
This repository contains the code and numerical experiments from the thesis "Phase Retrieval and Matrix Completion: Comparative Evaluation of Projection-Based Algorithms." The project investigates two fundamental problems in signal processing and data recovery:

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

## Usage

Run experiments for phase retrieval:
```bash
$ python phase_retrieval.py
```

Run experiments for matrix completion:
```bash
$ python matrix_completion.py
```

View the results and generate plots:
```bash
$ python visualize_results.py
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

## Key Algorithms
This project includes several projection-based algorithms:
- Alternating Projections (AP)
- Relaxed Alternating Projections (RAAR)
- Hybrid Input-Output (HIO)
- Relaxed Reflective Refraction (RRR)

Each algorithm is evaluated on multiple problem setups to assess:
- Convergence behavior
- Computational efficiency
- Robustness to noise
- Scalability with problem size

---

## Results
Detailed numerical results and analysis are available in the **results/** folder. These results provide actionable insights into selecting algorithms for specific problems and conditions.

---

## Citation
If you use this code in your research, please cite this repository:

```
@misc{harlap2025phase,
  author = {Yoav Harlap},
  title = {Phase Retrieval and Matrix Completion: Comparative Evaluation of Projection-Based Algorithms},
  year = {2025},
  url = {https://github.com/YoavHarlap/Phase_retrieval_and_matrix_completion_through_projection-based_algorithms}
}
```

---

## License
This project is licensed under the MIT License. See the LICENSE file for details.

---

## Contact
For questions or feedback, please contact Yoav Harlap at [your.email@example.com].
