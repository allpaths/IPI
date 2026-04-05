# Introduction to Shannon's Information Theory

An instructional Jupyter notebook deriving Shannon Information Entropy from first principles, based on Shannon's 1948 axiomatic approach.

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/allpaths/IPI/HEAD?filepath=IPI_1_Shannon_Entropy.ipynb)

## Contents

- **IPI_1_Shannon_Entropy.ipynb** — the interactive notebook
- Handwritten notes from the presenter embedded at each section

## Topics Covered

1. Shannon's four axioms
2. The information function I(p) = log_b(1/p)
3. Units: bits, nats, trits — and base conversion
4. Deriving Shannon entropy H(X)
5. Boundary cases (p=0, p=1)
6. Continuous entropy
7. Maximum entropy

## Running Locally

```bash
pip install numpy matplotlib jupyter
jupyter notebook IPI_1_Shannon_Entropy.ipynb
```