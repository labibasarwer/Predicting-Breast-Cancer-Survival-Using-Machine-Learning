# **Breast Cancer Survival Prediction Using Machine Learning**

## **Project Overview**
This project applies **machine learning models** to predict breast cancer survival outcomes using structured clinical data. By leveraging different classification algorithms, we assess **predictive accuracy, feature importance, and model interpretability** to support oncologists in identifying high-risk patients.

## **Project Stages**
This project consists of the following stages:

1. **Literature Review**  
   - Analyzed past research on breast cancer survival prediction models.  
   - Identified key clinical features influencing survival outcomes.  

2. **Data Collection & Preprocessing**  
   - Used structured patient data containing tumor size, receptor status, lymph node involvement, etc.  
   - Applied feature encoding, missing data handling, and class balancing (SMOTE).  

3. **Model Development & Evaluation**  
   - Trained **Logistic Regression, Random Forest, and Neural Networks**.  
   - Evaluated performance using **Accuracy, F1-Score, and ROC-AUC**.  
   - Identified key predictive factors using **SHAP values and feature importance**.  

4. **Survival Analysis & Case Studies**  
   - Integrated **Kaplan-Meier survival analysis** to validate ML model predictions.  
   - Added **real-world case studies** to demonstrate clinical applicability.  

5. **Ethical Considerations & Future Work**  
   - Addressed **data privacy, model interpretability, and bias mitigation**.  
   - Proposed **integration with Electronic Health Records (EHRs)** for real-world use.  

## **Repository Structure**
This repository contains the following files:

📂 **`/notebooks/`** – Jupyter Notebooks with data preprocessing, model training, and evaluation.  
📂 **`/data/`** – Processed dataset files used for training and testing models.  
📂 **`/reports/`** – Includes **Final Report (PDF)** and results analysis.  
📂 **`/visualizations/`** – Graphs, **feature importance plots, confusion matrices, and correlation heatmaps**.  
📂 **`/src/`** – Python scripts for preprocessing, feature selection, and model implementation.  
📄 **`README.md`** – This file provides an overview of the project and repository contents.  

## **Installation & Usage**
To run this project locally:
1. **Clone the repository**  
   ```sh
   git clone https://github.com/labibasarwer/Predicting-Breast-Cancer-Survival-Using-Machine-Learning.git
   cd breast-cancer-survival
   ```
2. **Install dependencies**  
   ```sh
   pip install -r requirements.txt
   ```
3. **Run Jupyter Notebook**  
   ```sh
   jupyter notebook
   ```
4. **Navigate to** `/notebooks/` and execute the scripts step by step.

## **Results Summary**
- **Random Forest achieved the best performance** with **93.62% accuracy**.  
- **Tumor size, lymph node involvement, and hormone receptor status were key predictors.**  
- **Deep learning models performed well but required more computational power.**  

## **Future Improvements**
- **Enhance interpretability** using **explainable AI (SHAP values, LIME).**  
- **Expand dataset** by integrating genomic and treatment-related data.  
- **Deploy as a web application** to allow oncologists to use predictions interactively.  

## **Contributors**
- **[Labiba Sarwer]** – Data Analysis & Model Implementation  
- **[Predicting Breast Cancer Survival Using 
Machine Learning Techniques
]** – Research & Report Writing  

## **License**
This project is licensed under the **MIT License** – feel free to modify and use it.
