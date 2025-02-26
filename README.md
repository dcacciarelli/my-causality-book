# Causality in Electricity Markets

![Book Logo](logo_thick_v2.png)

## Overview
*Causality in Electricity Markets* is a comprehensive guide to understanding and applying **causal inference techniques** in electricity markets. The book provides a structured introduction to **causal reasoning, statistical modeling, and machine learning methods** for uncovering cause-and-effect relationships in energy systems.

## Why This Book?
In modern electricity markets, **predictive models** alone are often insufficient. Understanding **causal mechanisms** is essential for:
- Identifying **true drivers** of market behaviors.
- Developing **effective policies** and interventions.
- Improving **forecasting models** with causal structure.

This book bridges the gap between **causal theory and practical applications**, offering real-world case studies in electricity market analysis.

## Table of Contents
The book is divided into five key sections:

1. **Introduction to Causal Inference**  
   - Causal vs. predictive models  
   - Directed Acyclic Graphs (DAGs)  
   - Structural Causal Models (SCM)  

2. **Causal Discovery**  
   - Learning causal structures from data  
   - Semi-parametric algorithms: LiNGAM, VAR-LiNGAM, ANMs
   
3. **Causal Inference Methods**  
   - Instrumental Variables (IV)  
   - Propensity Scores and Matching  
   - Double Machine Learning (DML)  
   
4. **Interpretability & Market Applications**  
   - Shapley values & Partial Dependency Plots  
   - Impulse response functions  
   - Case studies in electricity markets  

5. **Experimental Design & Data Collection**  
   - A/B testing  
   - Bandit algorithms  
   - Active learning  

## Getting Started
### Requirements
To reproduce examples in this book, install the following Python libraries:
```bash
pip install numpy pandas statsmodels scikit-learn dowhy matplotlib networkx
```
### Running the Notebooks
Jupyter notebooks are provided for hands-on learning:
```bash
git clone https://github.com/your-repo/causality-in-electricity-markets.git
cd causality-in-electricity-markets
jupyter notebook
```
## Authors
**Davide Cacciarelli**  
Research Associate, **Imperial College London**  
Expert in **causal inference, machine learning, and energy markets**  
[Personal Website](https://sites.google.com/view/dcacciarelli) | [Email](mailto:d.cacciarelli@imperial.ac.uk)

**Pierre Pinson**  
Chair of Data-centric Design Engineering, **Imperial College London**  
Editor-in-Chief, **International Journal of Forecasting**  
[Personal Website](https://pierrepinson.com/)

## Citation
If you use this book in your research, please cite:
```
@book{cacciarelli2024causality,
  author    = {Davide Cacciarelli, Pierre Pinson},
  title     = {Causality in Electricity Markets},
  publisher = {Imperial College London Press},
  year      = {2024}
}
```

## Contact
For inquiries, please reach out to [d.cacciarelli@imperial.ac.uk](mailto:d.cacciarelli@imperial.ac.uk).
