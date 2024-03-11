# Heart-Health-Analysis-Initiative

This project focuses on conducting Exploratory Data Analysis (EDA) on a heart disease dataset sourced from the UC Irvine Machine Learning Repository. The primary objective is to extract insights from the dataset, identify underlying patterns, and establish a foundation for building a heart disease detection model.

## Technologies and Tools Used

- **Python**: Main programming language utilized for data analysis and visualization.
- **Libraries and Packages**:
  - **ucimlrepo**: Python package employed for fetching datasets from the UC Irvine Machine Learning Repository.
  - **pandas**: Powerful library for data manipulation and analysis.
  - **numpy**: Library for performing numerical operations in Python.
  - **matplotlib** and **seaborn**: Libraries for generating visualizations.
  - **scikit-learn**: Machine learning library providing tools for data analysis and modeling.
- **Google Colab**: Online platform utilized for collaborative Python code execution.

## Key Dataset Features

The heart disease dataset comprises various features such as age, gender, chest pain type, resting blood pressure, cholesterol levels, and other health indicators. The target variable 'num' signifies the presence (1) or absence (0) of heart disease.

## Highlights of Exploratory Data Analysis

- Identification and conversion of categorical variables to enhance representation.
- Assessment for missing values ensuring dataset completeness.
- Observations on the distribution of target classes, indicating a somewhat balanced dataset.
- Generation of descriptive statistics and visualizations to provide an overview of dataset characteristics.

## Data Preprocessing

- Identification and conversion of categorical columns to object type.
- Examination of unique values and value counts in specific categorical columns.

## Statistical Analysis and Visualization

- Computation of basic statistics to gain insights into numerical feature tendencies and variabilities.
- Creation of count plots to visualize categorical variable distributions with respect to the target variable.
- Generation of pair plots and scatter plots to analyze relationships between continuous features and the target variable.

## Model Training and Evaluation

### Logistic Regression Model

- Utilization of Logistic Regression for initial binary classification.
- Division of dataset into training and testing sets.
- Training and evaluation of the model, yielding accuracy score, classification report, and confusion matrix.

### Random Forest Classifier Model

- Implementation of Random Forest Classifier to explore ensemble model performance.
- Training and evaluation on the same dataset, with comparison against Logistic Regression model metrics.

### Support Vector Machine (SVM) Model

- Employment of Support Vector Machine (SVM) as an alternative to investigate non-linear data relationships.
- Training, evaluation, and comparison of performance metrics with other models.

## Conclusion

This exploratory data analysis initiative serves as a fundamental step in comprehending patterns and characteristics inherent in the heart disease dataset. Future endeavors may include feature engineering, advanced modeling techniques, and fine-tuning to enhance the accuracy and robustness of the heart disease detection model.

**Dataset Link:** [UCI Heart Disease Dataset](https://archive.ics.uci.edu/dataset/45/heart+disease)