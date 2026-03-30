# Contributing to Harmonic Resonance Fields (HRF)

Thank you for your interest in contributing to **Harmonic Resonance Fields (HRF)**. This project is a research-driven, physics-informed machine learning framework focused on resonance-based classification, spectral learning, and robust time-series analysis.

This repository is structured as a **research + engineering hybrid project**, and contributions are welcome through **GSSoC 2026**.

---

# Table of Contents

1. Project Structure
2. Ways to Contribute
3. Getting Started
4. Development Setup
5. Contribution Workflow
6. Coding Guidelines
7. Documentation Guidelines
8. Research Contributions
9. Issue Guidelines
10. Pull Request Guidelines
11. Good First Issues (GSSoC)
12. Code of Conduct

---

# Project Structure

```
.
├── .github/workflows/        # CI/CD and automation workflows
├── 1/                        # Early HRF prototypes, notebooks, and benchmarks
├── docs/                     # Technical monograph and documentation
├── HRF Codes/                # Conference, EEG, and final HRF implementations
├── HRF-Engine/               # Core HRF engine (21D, 26D, generalized HRF)
├── Research Paper/           # Research paper, white paper, and publication files
├── README.md                 # Main project overview
├── Contributing.md           # Contribution guidelines
├── LICENSE
├── SECURITY.md
└── .gitignore
```

### Important Directories

| Folder            | Description                                                      |
| ----------------- | ---------------------------------------------------------------- |
| `HRF-Engine/`     | Core HRF algorithm implementations                               |
| `HRF Codes/`      | Application-specific HRF implementations (EEG, Conference, etc.) |
| `docs/`           | Technical documentation and monograph                            |
| `Research Paper/` | Paper, whitepaper, and publication material                      |
| `1/`              | Experimental notebooks, early versions, benchmarks               |

---

# Ways to Contribute

## Code Contributions

* Improve HRF engine
* Optimize GPU implementation
* Implement multi-class HRF
* Implement regression HRF
* Improve Harmonic Forest
* Add new resonance kernels
* Improve evolutionary optimization

## Documentation Contributions

* Improve README
* Improve Wiki
* Write tutorials
* Add diagrams
* Add mathematical derivations

## Research Contributions

* Mathematical analysis of HRF
* Kernel analysis
* HRF vs SVM comparison
* HRF vs Random Forest comparison
* HRF vs XGBoost comparison
* Spectral analysis of HRF
* Phase invariance proof

## Testing Contributions

* Add unit tests
* Add benchmark tests
* Test on new datasets
* GPU vs CPU benchmarks

---

# Getting Started

## Step 1 — Fork the Repository

## Step 2 — Clone

```bash
git clone https://github.com/YOUR-USERNAME/Harmonic-Resonance-Forest.git
cd Harmonic-Resonance-Forest
```

## Step 3 — Create Branch

```bash
git checkout -b feature/your-feature-name
```

---

# Development Setup

## Requirements

* Python 3.10+
* NumPy
* SciPy
* scikit-learn
* CuPy (GPU)
* RAPIDS cuML (optional)
* Pandas
* Matplotlib

## Install

```bash
pip install -r requirements.txt
```

---

# Contribution Workflow

1. Fork repository
2. Clone fork
3. Create new branch
4. Make changes
5. Commit
6. Push
7. Open Pull Request

---

# Coding Guidelines

* Follow **PEP 8**
* Use meaningful variable names
* Add docstrings
* Write modular code
* Avoid hardcoding

### Example

```python
def resonance_kernel(distance, gamma, omega, phase):
    """Compute harmonic resonance response"""
    return np.exp(-gamma * distance**2) * np.cos(omega * distance + phase)
```

---

# Documentation Guidelines

Documentation should include:

* Explanation
* Mathematical intuition
* Equations
* Diagrams
* Example usage

Documentation locations:

```
docs/
README.md
wiki/
notebooks/
```

---

# Research Contributions

Research-style contributions are highly encouraged. Suggested topics:

* Mathematical theory of HRF
* Resonance kernel analysis
* Decision boundary analysis
* Spectral domain interpretation
* Phase invariance proof
* Noise robustness experiments
* Time-series benchmarking

Research contributions should include:

* Problem
* Method
* Experiment
* Results
* Conclusion

---

# Issue Guidelines

When opening an issue:

* Use clear title
* Describe problem
* Include logs/screenshots
* Suggest solution if possible

### Example Issue Titles

* "Bug: HRF GPU memory overflow"
* "Feature: Add multi-class HRF"
* "Docs: Add HRF mathematical derivation"

---

# Pull Request Guidelines

Before submitting PR:

* Code runs
* No errors
* Documentation updated
* Clear commit message

### PR Title Format

```
[Feature] Added multi-class HRF
[Fix] Fixed GPU bug
[Docs] Added math explanation
[Benchmark] Added dataset test
```

---

# Good First Issues (GSSoC)

### Beginner

* Improve documentation
* Add comments to code
* Add example notebooks
* Add visualization plots
* Write function documentation

### Intermediate

* Multi-class HRF
* Regression HRF
* FFT optimization
* Add dataset loaders

### Advanced

* GPU optimization
* New resonance kernels
* Mathematical proof work
* HRF vs Deep Learning comparison

---

# Code of Conduct

Be respectful and collaborative.

This project is research-oriented and aims to build a community around **physics-informed machine learning**.

---

# Final Note

HRF is a research project. Contributors are encouraged to think about:

* Physics
* Mathematics
* Signal Processing
* Machine Learning Theory

**Build not just code — build understanding.**
