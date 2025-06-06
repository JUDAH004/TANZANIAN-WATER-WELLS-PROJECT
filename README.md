
# 💧 CLASSIFICATION PROJECT:TANZANIAN WATER WELLS.

## 📝 Project Description
This project tackles a real-world problem from **Tanzania**, where thousands of water pumps are installed across rural regions. The goal is to **predict the operational status** of a water pump (`functional`, `non functional`, or `functional needs repair`) using historical and geographic data. This information is critical for resource allocation, maintenance prioritization, and policy decisions.


## 📊 Dataset Overview

- **Features include**:  
  - **Categorical**: installer, basin, scheme_management, etc.  
  - **Numerical**: amount_tsh, gps_height, population, etc.  
  - **Binary**: public_meeting, permit  

- **Target Variable**:  
  - `functional`  
  - `non functional`  
  - `functional needs repair`

---

## ✅ Project Steps

1. **Data Cleaning**  
   - Missing value treatment  
   - Outlier handling  
   - Type casting

2. **Feature Engineering**  
   - Grouping rare categories  
   - Handling categorical, continuous, and binary features separately  
   - Optional one-hot encoding or ordinal encoding

3. **Modeling**  
   - Baseline: Logistic Regression  
   - Simple: Decision Tree Classifier  
   - Evaluation using precision, recall, F1-score, and ROC AUC

4. **Evaluation & Visualization**  
   - Classification reports  
   - Confusion matrix  
   - ROC Curve (Macro-average for multiclass)

---

## 📈 Results Summary

| Metric        | Logistic Regression | Decision Tree |
|---------------|---------------------|----------------|
| Accuracy      | 72.3%               | **74.8%**      |
| Precision     | 69.7%               | **74.9%**      |
| Recall        | 72.3%               | **74.8%**      |
| F1 Score      | 69.3%               | **74.9%**      |
| AUC (macro)   | ~0.78               | **~0.81**      |

The **Decision Tree model** outperformed the baseline Logistic Regression in all key metrics.

---

## 📊 Visualizations
- 1. Feature importance bar chart 
- Distribution of target class against numerical features 
- confusion matrix
- distribution of target class
- Classification reports

---

## 📂 Repository Structure

Data/ → Folder containing datasets for analysis

images/ → Folder containing key visualizations obtained from the analysis

README.md → This document outlining project details

project_notebook.ipynb → Jupyter Notebook containing the full analysis

presentation 2.pdf → Presentation summarizing key insights and business recommendations for investors

## Tools & Technologies
The project utilizes the following tools and technologies:

> Programming Language
1. Python: Used for data analysis, visualization, and statistical computations.
Libraries and Frameworks

> Data Manipulation and Analysis:

1. Pandas: For data cleaning, manipulation, and merging datasets.
2. NumPy: For numerical computations and handling arrays.
> Data Visualization:

1. Matplotlib: For creating static, interactive, and publication-quality visualizations.
2. Seaborn: For advanced statistical data visualization.
> Statistical Analysis:

1. SciPy: For performing statistical tests like t-tests and correlation analysis.
String and Data Parsing:

ast: For safely evaluating strings containing Python literals (e.g., converting stringified lists to actual lists).
> Machine Learning 
1. Scikit- learn - Machine learning library

zipfile: For extracting compressed files.
os: For file path and directory management.
## 🔮 Future Improvements

- Model tuning (e.g., GridSearchCV or RandomizedSearchCV)  
- Try more complex models: Random Forest, XGBoost  
- Incorporate SMOTE or class weighting to improve minority class performance  
- Deploy using Flask or Streamlit

---
## Technologies used
## 👤 Author
JUDAH SAMUEL
Data Science Enthusiast | [LinkedIn](JUDAH SAMUEL) | [GitHub](JUDAH004)
