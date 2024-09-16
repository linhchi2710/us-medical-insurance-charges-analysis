# US Medical Insurance Charges Analysis

## Overview
This project investigates the factors that influence medical insurance charges in the US. Using a dataset of over 1,300 insurance records, the analysis explores the impact of various factors such as age, gender, BMI, smoking status, and region on insurance costs. The goal is to identify key cost drivers and provide insights that could help in understanding how different factors contribute to medical insurance charges.

## Objectives
- To analyze the distribution of medical insurance charges and identify patterns.
- To explore the impact of demographic and lifestyle factors (age, gender, BMI, smoking status, region) on insurance charges.
- To use statistical and machine learning models to predict insurance costs based on these factors.

## Dataset
The dataset contains 1,338 records with the following fields:
- **Age**: Age of the individual.
- **Sex**: Gender of the individual (female, male).
- **BMI**: Body Mass Index.
- **Children**: Number of children/dependents covered by the insurance.
- **Smoker**: Smoking status of the individual (yes, no).
- **Region**: Residential region in the US (northeast, northwest, southeast, southwest).
- **Charges**: Individual medical insurance charges billed by health insurance.

## Key Findings
- **Smoking Status**: A significant driver of insurance costs, with smokers incurring much higher charges than non-smokers.
- **Age and BMI**: Both positively correlated with insurance charges; older individuals and those with a higher BMI tend to have higher medical costs.
- **Regional Differences**: Insurance charges vary by region, with some regions showing consistently higher costs.
- **Gender and Children**: Less significant impact compared to other factors but still provide useful insights into specific patterns.

## Tools and Technologies
- **Python**: Programming language for data analysis.
- **Pandas and NumPy**: Libraries for data manipulation and statistical operations.
- **Matplotlib and Seaborn**: Libraries for data visualization.
- **Scikit-Learn**: For regression analysis and modeling.

## Analysis and Visualizations
- **Exploratory Data Analysis (EDA)**: Examined the distribution of charges and demographic features.
- **Correlation Analysis**: Identified significant factors affecting insurance charges.
- **Regression Analysis**: Predicted insurance charges using linear regression models.
- **Data Visualizations**:
- **Box plots**: For comparing insurance charges across different regions and demographic groups.
- **Regression plots**: To show relationships between age, BMI, smoking status, and charges.
- **Histograms**: To illustrate the distribution of insurance charges.

## Dataset
The dataset used in this analysis is publicly available on Kaggle and can be downloaded from the following link:
[US Medical Insurance Costs Dataset on Kaggle]: (https://www.kaggle.com/datasets/mirichoi0218/insurance)
