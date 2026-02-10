# Credit Check Approval with an Accurate Decision-Making System Using Machine Learning  
## Dissertation Prototype Repository

## Abstract
This repository presents the prototype implementation and experimental artifacts associated with the MSc Data Science dissertation entitled **“Credit Check Approval with an Accurate Decision-Making System Using Machine Learning Methods.”** The research investigates the applicability of supervised machine learning techniques to improve the accuracy, reliability, and interpretability of credit approval decision systems.  

The repository supports the empirical evaluation reported in the final dissertation and is intended to provide transparency, reproducibility, and methodological clarity for academic review and research reference.

---

## Academic Context
- **Degree Program**: Master of Science in Data Science  
- **Institution**: Middlesex University  
- **Module**: CST 4090 – Dissertation  
- **Candidate**: Dhruvik Patel (Student ID: M00906119)  
- **Submission Date**: October 2023  

This repository constitutes a **research prototype** and does not represent a deployable or production-grade financial decision system.

---

## Research Motivation
Credit approval processes in financial institutions have traditionally relied on rule-based scorecard systems and heuristic-driven evaluation frameworks. While effective under constrained assumptions, such approaches often lack the capacity to model non-linear relationships and complex interactions present in modern financial datasets.

This research examines whether machine learning–based classifiers can enhance creditworthiness assessment by:
- Capturing higher-order feature interactions,
- Improving predictive accuracy over traditional methods, and
- Supporting more consistent and data-driven credit approval decisions.

---

## Research Objectives
The primary objectives of this dissertation prototype are as follows:

1. To design and implement a machine learning–based framework for credit check approval.
2. To conduct a comparative evaluation of Logistic Regression, Decision Tree, and Random Forest classifiers.
3. To assess model performance using standard classification metrics.
4. To analyse feature importance and interpretability in credit scoring contexts.
5. To examine ethical considerations related to fairness, bias, and data privacy.

---

## Methodological Overview
The experimental workflow implemented in this repository consists of the following stages:

- **Data Generation**: Creation of synthetic datasets that emulate real-world credit profiles while preserving privacy.
- **Data Pre-processing**: Cleaning, handling missing values, feature encoding, and normalization.
- **Model Training**: Supervised learning using Logistic Regression, Decision Tree, and Random Forest algorithms.
- **Evaluation**: Quantitative assessment using accuracy, precision, recall, F1-score, and ROC analysis.
- **Interpretation**: Examination of feature relevance and model behavior.

Across comparative evaluations, the Random Forest classifier demonstrated superior performance in terms of predictive accuracy and robustness.

---

## Repository Structure
Dissertation-Credit-Score-ML/
├── README.md
├── report/
│ └── Dissertatintion_Report_M00906119-.pdf
├── poster/
│ └── M00906119_Poster.pptx
├── notebooks/
│ ├── Analysis_RF.ipynb
│ ├── Analysis_LR.ipynb
│ ├── Analysis_Decision_tree.ipynb
│ ├── Prediction Model and Accuracy test M00906119.ipynb
│ ├── Diagram__Using_ML.ipynb
│ └── Synthetic_Dataset_generation_code.ipynb
├── data/
│ ├── train.csv
│ └── Credit_Score_Accuracy_Data.csv
└── raw materials/

 
---

## Component Description

### Dissertation Report
The `report/` directory contains the final dissertation document, including the literature review, methodology, experimental results, discussion, limitations, and conclusions.

### Experimental Notebooks
The `notebooks/` directory includes Jupyter notebooks documenting:
- Model-specific analyses,
- Comparative performance evaluations,
- Synthetic data generation procedures,
- Conceptual and methodological diagrams.

### Datasets
The `data/` directory contains synthetically generated datasets used for training and evaluation. No real personal or financial data is included.

---

## Ethical and Research Considerations
- All datasets are synthetically generated to mitigate privacy and confidentiality risks.
- Potential sources of algorithmic bias and fairness concerns are discussed within the dissertation.
- Model interpretability and responsible AI principles are explicitly considered.
- The prototype is intended exclusively for academic analysis and evaluation.

---

## Key Findings
- Ensemble-based learning methods outperform baseline statistical models in credit classification tasks.
- Income stability, credit history length, and debt-related indicators emerge as dominant predictive features.
- Machine learning approaches offer improved flexibility compared to traditional scorecard systems, though ethical oversight remains essential.

---

## Technologies and Tools
- Python  
- pandas, numpy  
- scikit-learn  
- plotly  
- Jupyter Notebook  

---

## Usage and Limitations
This repository represents a **research prototype** developed for academic purposes. The models and analyses herein are not validated for real-world credit approval or regulatory compliance. Any operational deployment would require extensive testing, governance review, and ethical validation.

---

## Author
**Dhruvik Patel**  
MSc Data Science  
Middlesex University  

---

## Citation
If this work is referenced in academic or research contexts, please cite the dissertation document included in this repository.

---

## License
This repository is released for **educational and research use only**.
