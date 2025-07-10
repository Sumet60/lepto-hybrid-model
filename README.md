# lepto-hybrid-model

Code and data for the manuscript submitted to *PLOS Computational Biology* titled:  
**"Hybrid neural–mechanistic modeling of leptospirosis transmission with environmental drivers: Evidence from Thailand"**
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.15853532.svg)](https://doi.org/10.5281/zenodo.15853532)

---

## Overview

This repository contains the code, data, and reproducibility files for running the hybrid modeling framework developed in the study. The model combines neural network components (LSTM) with a mechanistic SIR-based ODE system, incorporating environmental covariates such as rainfall, temperature, and water indices to simulate and forecast leptospirosis transmission dynamics.

---

## Environment

This project was developed and tested using:

- **Python**: 3.9.16  
- **conda**: 24.1.2  
- **Jupyter Notebook**: 7.0.8  
- **pandas**: 2.2.2  
- **matplotlib**: 3.9.2  
- **numpy**: 1.26.4  
- **torch**: 2.4.1+cpu  
- **scikit-learn**: 1.5.1  

## 📖 How to cite

If you use this work, please cite:

> Sumet Khumphairan\*, Sudarat Chadsuthi\*, Peter Fransson, Yichao Liu, Charin Modchang, Joacim Rocklöv, Ekaterina Kostina (2025).  
> *Hybrid modeling framework for leptospirosis dynamics.* Zenodo. https://doi.org/10.5281/zenodo.15853532

### 🔖 BibTeX

```bibtex
@misc{khumphairan2025hybrid,
  author       = {Sumet Khumphairan and Sudarat Chadsuthi and Peter Fransson and Yichao Liu and Charin Modchang and Joacim Rocklöv and Ekaterina Kostina},
  title        = {Hybrid modeling framework for leptospirosis dynamics},
  year         = 2025,
  publisher    = {Zenodo},
  doi          = {10.5281/zenodo.15853532},
  url          = {https://doi.org/10.5281/zenodo.15853532}
}


