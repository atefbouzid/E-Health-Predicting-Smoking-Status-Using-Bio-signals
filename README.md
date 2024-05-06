## E-Health: Predicting Smoking Status Using Bio-signals

### Project Overview
This repository contains the code and documentation for a data analysis project focused on predicting smoking status using bio-signals. Leveraging machine learning techniques, the project aims to develop a model capable of identifying individuals who are smokers or non-smokers based on their health data.

### Data Description
The project utilizes a dataset containing information on 159,256 individuals, including bio-signals, demographic details, and smoking status. The dataset comprises 24 numerical features, with the target variable "smoking" being binary, indicating whether an individual is a smoker (1) or not (0).

### Methodology
The project involved the following key steps:
- **Data Exploration and Visualization:** Extensive analysis was conducted to understand the distribution of features, identify potential outliers, and explore relationships between variables.
- **Feature Engineering:** New features were created to capture additional information and potentially improve model performance, such as BMI, waist-to-height ratio, and blood pressure categories.
- **Data Preprocessing:** Outliers were handled using domain-specific thresholds, and irrelevant features were dropped to improve data quality and model efficiency.
- **Model Training and Evaluation:** Several machine learning models were trained and compared, including Random Forest, LightGBM, CatBoost, and XGBoost. Performance was evaluated using metrics such as AUC-ROC, precision, recall, and F1-score.
- **Ensemble Modeling:** An ensemble model was created by averaging the predictions of LightGBM and CatBoost, leading to improved generalization and robustness.
- **Cross-Validation:** K-fold cross-validation was employed to assess model performance and mitigate overfitting.

### Results
The ensemble model achieved a competitive score of 0.87 in a Kaggle competition.

### Future Work
- Hyperparameter tuning for individual models and the ensemble.
- Incorporation of additional data sources for richer insights.
- Exploration of model interpretability techniques for understanding prediction drivers.

### Repository Contents
- **data_analysis_report.pdf:** Detailed report outlining the project methodology, results, and conclusions.
- **Notebook.ipynb:** Jupyter Notebook.


### Requirements
- Python 3.12
- Libraries:
  - xgboost
  - catboost
  - lightgbm
  - seaborn
  - tabulate
  - scikit-learn
  - matplotlib
  - pandas
  - numpy
  - scipy

### Instructions
- Install the required libraries.
- Run the Jupyter Notebooks in order to reproduce the analysis and results.

### Contact
👤 [Atef Bouzid](https://www.linkedin.com/in/atefbouzid/)
📧 [Email](atef.bouzid@ept.ucar.tn)
