# Emerging Technologies Assessment

**Student:** Hasan Murtaza (g00419888)  
**Module:** Emerging Technologies.  

---

## Purpose

This repository contains solutions to five problems exploring classical and quantum algorithms for Boolean function analysis. The assessment progresses from generating random Boolean functions to implementing the Deutsch-Jozsa quantum algorithm, demonstrating exponential quantum advantage over classical approaches.

### Problems Overview

1. **Random Boolean Functions** - Generate random constant and balanced 4-bit Boolean functions.
2. **Classical Algorithm** - Implement classical algorithm to classify functions (requires up to 9 queries)
3. **Quantum Oracles** - Build quantum oracles for single-bit Boolean functions.
4. **Deutsch's Algorithm** - Implement Deutsch's algorithm (1 quantum query vs 2 classical)
5. **Deutsch-Jozsa Algorithm** - Scale to 4-bit functions showing 9× quantum speedup.

---

## Setup Instructions

### Prerequisites
- Python 3.12+
- pip
- Jupyter Notebook

### Installation

1. Clone the repository:
```bash
git clone https://github.com/HasanMurtez/emerging-technologies.git
cd emerging-technologies
```

2. Install required packages:
```bash
pip install -r requirements.txt
```

3. Launch Jupyter Notebook:
```bash
jupyter notebook problems.ipynb
```

---

## Running the Code

From Jupyter:
- **Run All:** `Kernel` -> `Restart & Run All`
- **Run Individual Problems:** Execute cells sequentially within each problem section

All code cells should execute without errors. Total execution time: ~15 seconds.

---

## Dependencies

All required packages are listed in `requirements.txt`:
- `numpy` - Numerical computing
- `qiskit` - Quantum computing framework
- `qiskit-aer` - Quantum circuit simulation
- `matplotlib` - Visualization
- `jupyter` - Notebook environment
- `ipykernel` - Jupyter kernel support
- `pylatexenc` - Circuit diagram rendering
- `pandas` - Data display

---

## Key Results

- **Problem 1:** Successfully generates random 4-bit constant and balanced functions.
- **Problem 2:** Classical algorithm requires up to 9 queries worst-case.
- **Problem 3:** All 4 single-bit oracles implemented and verified.
- **Problem 4:** Deutsch's algorithm achieves 100% accuracy with 1 quantum query.
- **Problem 5:** Deutsch-Jozsa correctly classifies 4-bit functions with 1 query (vs 9 classical)

**Quantum Advantage:** 9× speedup for 4-bit functions, scales exponentially with input size.
