# Student Depression Analysis

This repository contains a data science project aimed at analyzing factors associated with student depression. The project uses a dataset with over **27,901 records** and **18 columns**, focusing on various demographic, academic, and psychological variables.

## Table of Contents
1. [Project Overview](#project-overview)
2. [Dataset](#dataset)
3. [Folder Structure](#folder-structure)
4. [Dependencies & Requirements](#dependencies--requirements)
5. [Usage](#usage)
6. [Project Flow](#project-flow)
7. [Key Findings](#key-findings)
8. [License](#license)
9. [Contact](#contact)

---

## Project Overview

- **Objective**: To explore, visualize, and build predictive models that identify risk factors for student depression and classify whether a student is likely to be depressed.
- **Methods**: Includes exploratory data analysis (EDA), outlier detection, data preprocessing, correlation analysis, and classification modeling (Random Forest, Logistic Regression, K-Nearest Neighbors). Also covers extended evaluations like confusion matrices, ROC curves, and hyperparameter tuning.

---

## Dataset

- **Name**: [Student Depression Dataset](https://www.kaggle.com/datasets/hopesb/student-depression-dataset)
- **Description**: Contains demographic and psychological factors such as age, gender, academic pressure, work pressure, financial stress, family history of mental illness, sleep duration, dietary habits, and more.
- **Size**: Over 27,901 records and 18 columns.

## Folder Structure

``` 
IA/
├─ README.md                  # This file
├─ student_depression_tournier_ouldali.ipynb   # Main Jupyter Notebook with the analysis
├─ requirements.txt           # Python dependencies list
```
## Dependencies & Requirements

- **Python 3.7+** recommended
- **pandas**
- **numpy** (optional if directly needed)
- **matplotlib**
- **seaborn**
- **scikit-learn** (for modeling, pipelines, and evaluation)
- **jupyter** (if you plan to run the `.ipynb` locally)

These can be installed via:

```bash
pip install -r requirements.txt
```



#### Add ssh to python if you have certificate issues when importing data

* MacOS
```bash
/Applications/Python\ 3.x/Install\ Certificates.command
```
* Windows
```bash
python -m pip install --upgrade certifi
```

## Usage

1. **Download or Clone** the repository.
2. **Install** the necessary libraries.
3. **Open** the notebook (e.g., `student_depression_tournier_ouldali.ipynb`) in Jupyter.
4. **Execute** the cells in order
5. **Interpret Results** using feature importance, classification reports, and confusion matrices.

---

## Project Flow

1. **Data Exploration**: Check distributions, missing values, outliers, and correlations.
2. **Preprocessing**: Handle missing values, encode categorical columns, scale numeric features.
3. **Model Building**: Train Random Forest, Logistic Regression, and KNN; compare accuracy and ROC–AUC.
4. **Feature Importance**: Identify key predictors from the Random Forest model.
5. **Hyperparameter Tuning**: Use grid search to optimize model parameters.
6. **Extended Analysis**: Examine confusion matrices, classification metrics, partial dependence plots for deeper insights.

---

## Key Findings

- **Suicidal Thoughts** exhibited the strongest positive correlation with depression.
- **Academic Pressure** and **Financial Stress** were also major predictors.
- **Age** showed a mild negative correlation (younger students potentially at higher risk).
- **Random Forest** generally performed well, improved further with hyperparameter tuning.
- Detailed metrics like precision, recall, and F1-score provided a nuanced view beyond simple accuracy.



