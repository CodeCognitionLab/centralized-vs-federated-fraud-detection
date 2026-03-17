# Centralized vs Federated Fraud Detection

This repository contains the implementation used in the research paper:

**"Centralized and Federated Learning Approaches for Financial Fraud Detection Across Heterogeneous Ecosystems"**

---

## Code Included

- Traditional Finance (TradFi) fraud detection experiments  
- FinTech fraud detection experiments  
- DeFi fraud detection experiments  
- Federated learning simulation  
- Data preprocessing pipeline  

---

## Datasets

The datasets used in this study are derived from publicly available sources:

- Credit Card Fraud Dataset (TradFi): [https://www.kaggle.com/datasets/nelgiriyewithana/credit-card-fraud-detection-dataset-2023]
- PaySim Dataset (FinTech): [(https://www.kaggle.com/datasets/mtalaltariq/paysim-data)]
- Elliptic Dataset (DeFi):[https://www.kaggle.com/datasets/ellipticco/elliptic-data-set] 

These datasets were **preprocessed and transformed** to generate the final datasets used in the experiments.

The processed datasets used in this study are publicly available at:  
[https://drive.google.com/drive/folders/1cMqD4Nbpf6XqFhKf8w-CZJOwo-oR2y2W?usp=drive_link]

---

## Reproducibility

- Fixed-seed experiments for reproducibility  
- Multiple random runs for robustness evaluation  
- Consistent preprocessing across centralized and federated models  
- Evaluation using F1-score and AUC-ROC metrics  

---

## Notes

- The original datasets are not redistributed due to their respective source policies.  
- All transformations applied to the datasets are included within the provided code and notebooks.  
