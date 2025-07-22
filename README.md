# Sleep Disorder prediction

## 📌 Project Overview

This machine learning project aims to predict whether a person has a sleep disorder or not, and if so, what type of sleep disorder it is. The dataset is preprocessed, visualized, and cleaned, and then used to train a classification model that predicts the type of sleep disorder a person may have.

## ✅ Steps Performed

1. **Data Collection**  
   Loaded the dataset (`sleep_disorder.csv`) containing salary features and labels.

2. **Data Cleaning**
   - Checked for null values and filled them with appropriate values
   - encoding all the required columns using label encoding and one-hot encoding  
   - Handled outliers using the IQR method

3.  **Data Visualizatio**
   - using boxplot to find outliers
   - Using a scatter plot, found relationship between two features
   - using histogram, found the frequency of that feature 
4.  **Data Preprocessing**   
   - selected all the required columns, which is called feature engineering
   - removed columns like sleep_disorder, Person ID
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
