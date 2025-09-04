# Iterative Domain Adaptation & Sequential Classification on Multi-Feature Datasets

## Overview
This repository contains coursework for **CS771: Machine Learning** (IIT Kanpur), under the supervision of **Prof. Piyush Rai**.  
The project is divided into **Task 1 (Sequential Classification)** and **Task 2 (Iterative Domain Adaptation)**, and is accompanied by a detailed PDF report.  

- **Task 1:** Implemented binary classifiers across three feature-diverse datasets, using PCA-based dimensionality reduction, logistic regression, SVMs, and distillation-based models.  
- **Task 2:** Designed an iterative domain adaptation framework using prototype-based learning and pseudo-labeling to refine classifiers on unlabeled data and handle distributional shifts.  
- **Results:** Achieved up to **15% improvement in cross-domain classification accuracy**, demonstrating robustness to domain shifts.  

---

## Repository Structure
```text
CS771/
├── Task1.ipynb                  # Jupyter notebook for Task 1 experiments
├── Task2.ipynb                  # Jupyter notebook for Task 2 experiments
├── report.pdf                   # Project report with methodology, results, and analysis
├── requirements.txt             # Python dependencies
└── README.md                    # Project documentation

## Setup Instructions

* Activate virtual environment:
  
```bash
python3 -m venv venv
source venv/bin/activate
```
* Install dependencies:
```bash
pip install -r requirements.txt
```

``` text
pandas
numpy
scikit-learn
matplotlib
seaborn
joblib
```


