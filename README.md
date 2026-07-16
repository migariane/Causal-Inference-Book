# Computational Causal Inference for Applied Researchers

**A Practical Guide for Epidemiologists and Biostatisticians**

**Authors:** Miguel Angel Luque-Fernandez & Matthew J. Smith

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.20677995.svg)](https://doi.org/10.5281/zenodo.20677995)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A Quarto book introducing causal inference from a beginner's perspective, leading to advanced computational methods using **R** and **Stata**. Available online at **[migariane.github.io/Causal-Inference-Book](https://migariane.github.io/Causal-Inference-Book/)**.

## How to cite

If you use this book in your research or teaching, please cite it as:

> Luque-Fernandez, M. A., & Smith, M. J. (2026). *Computational Causal Inference for Applied Researchers: A Practical Guide for Epidemiologists and Biostatisticians*. Universidad de Granada. https://doi.org/10.5281/zenodo.20677995

```bibtex
@book{luque-fernandez2026causal,
  title     = {Computational Causal Inference for Applied Researchers:
               A Practical Guide for Epidemiologists and Biostatisticians},
  author    = {Luque-Fernandez, Miguel Angel and Smith, Matthew J.},
  year      = {2026},
  publisher = {Universidad de Granada},
  doi       = {10.5281/zenodo.20677995},
  url       = {https://migariane.github.io/Causal-Inference-Book}
}
```

The book is permanently archived on [Zenodo](https://zenodo.org/). Each release receives a versioned DOI; please cite the specific DOI of the version you used.

## Chapters

| Part | Chapter | Topic |
|------|---------|-------|
| I: Foundations | 1 | Introduction to Causal Inference |
| | 2 | Regression Adjustment |
| II: G-Methods | 3 | The G-Formula |
| | 4 | Propensity Score Methods |
| III: Advanced Methods | 5 | Double-Robust Estimators (AIPW, TMLE) |
| | 6 | Causal Inference for Longitudinal Data |
| | 7 | Mediation Analysis |
| IV: Sensitivity & Discussion | 8 | Sensitivity Analysis |
| | 9 | Discussion |

## Features

- ~65 R code listings with reproducible examples
- Stata implementations for key methods
- Theorem, definition, example, and proof callout environments
- Per-chapter glossaries defining key terms
- APA-formatted bibliography with 700+ references
- UGR-branded visual theme

## Build

```bash
quarto render
```

Output lands in `docs/`.

## License

MIT — see [LICENSE](LICENSE).
