# Predicting Patient Readmissions Using Machine Learning on Diabetes Data  

## Overview  
This project applies machine learning techniques to predict hospital readmissions among diabetic patients using the **Diabetes 130-US hospitals dataset**. The workflow includes data preprocessing, exploratory data analysis (EDA), feature selection, and model development using various machine learning models. A **grid search** was performed to optimize hyperparameters for each model.  

## Dataset  
The dataset used in this project is the **Diabetes 130-US hospitals dataset**, which contains patient records from 130 hospitals across the United States between 1999-2008. You can access the dataset here:  
🔗 [Diabetes 130-US Hospitals Dataset](https://archive.ics.uci.edu/dataset/296/diabetes+130-us+hospitals+for+years+1999-2008)  

## Project Structure  
The pipeline consists of four Jupyter notebooks that should be run in sequence:  

1. **`data_preprocessing.ipynb`** – Cleans and prepares the dataset by handling missing values, encoding categorical features, and standardizing numerical variables.  
2. **`eda.ipynb`** – Performs exploratory data analysis, visualizations, and class distribution checks.  
3. **`feature_selection.ipynb`** – Uses ANOVA F-tests, PCA, and Recursive Feature Elimination (RFE) to select the most relevant features.  
4. **`model_development.ipynb`** – Trains, tunes, and evaluates multiple machine learning models using a parallelized **grid search** for hyperparameter optimization.  

## Models & Grid Search Hyperparameters  
The following models were used, each optimized with a grid search:  

- **XGBoost**  
- **AdaBoost**  
- **Naive Bayes**  
- **Decision Tree**  
- **Random Forest**  
- **Logistic Regression**  
- **SVM**  
- **Gradient Boosting**  
- **KNN**  
- **Extra Trees**  

Each model was trained using **grid search with parallel computation** to optimize performance. Evaluation was based on metrics like **accuracy, precision, recall, F1-score, AUC-ROC**, and visualized through **ROC curves**.  

## Installation & Dependencies  
Ensure you have Python 3 and the required dependencies installed. You can install them using:  
```bash
pip install -r requirements.txt
```

## Running the Project  
Execute the notebooks in the order mentioned above.  

## Conclusion  
The project demonstrates the potential of machine learning in healthcare predictive modeling, helping healthcare providers reduce readmission rates for diabetic patients.  

## Project Information  
- **Course:** Data Science (CSCI 6409)  
- **Term:** Summer 2024  
- **Institution:** Dalhousie University  
- **Author:** Akhlaqur Rahman Sabby  

## Acknowledgments  
This project was completed as part of **Data Science (CSCI 6409) coursework at Dalhousie University (Summer 2024)**. Special thanks to the course instructor for guidance and support.
