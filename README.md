# Sleep Disorder prediction

## 📌 Project Overview

This machine learning project aims to predict whether a person having any sleep disorder or not if yes then what it is. The dataset is preprocessed, visualized, and cleaned, and then used to train a classification model that predicts sleep disorder of a person.

## ✅ Steps Performed

1. **Data Collection**  
   Loaded the dataset (`sleep_disorder.csv`) containing salary features and labels.

2. **Data Cleaning**
   - Checked for null values and filled them with appropriate values
   - encoding all the required columns using label encoding and one hot encoding  
   - Handled outliers using the IQR method

3.  **Data Visualizatio**
   - using boxplot found outliers
   - using scatter plot found relationship between two features
   - using hisogram found the frequency of that feature 
5.  **Data Preprocessing**   
   - selected all the required columns which is called feature engineering
   - removed columns like sleep_disorder,Person id
   - Split the dataset into training and testing sets

5. **Model Selection & Training**  
   - Used **Decision tree lassifier** to evalute the data  
   - Evaluated the model with classification metrics

## 📊 Libraries Used

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`
