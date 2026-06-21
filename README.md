# Wine Quality Prediction using Machine Learning

## Project Overview

This project predicts whether a wine is Good Quality or Bad Quality using Machine Learning techniques.

The model analyzes physicochemical properties of wine, performs exploratory data analysis, trains a Random Forest Classifier, and predicts wine quality.

---

## Features

- Data Cleaning
- Exploratory Data Analysis
- Correlation Heatmap
- Feature Engineering
- Binary Classification
- Random Forest Model
- Accuracy Evaluation
- Prediction System

---

## Dataset Features

- Fixed Acidity
- Volatile Acidity
- Citric Acid
- Residual Sugar
- Chlorides
- Free Sulfur Dioxide
- Total Sulfur Dioxide
- Density
- pH
- Sulphates
- Alcohol
- Quality

Target Variable:

- 1 → Good Quality Wine (Quality >= 7)
- 0 → Bad Quality Wine (Quality < 7)

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Project Workflow

1. Import Libraries
2. Load Dataset
3. Explore Dataset
4. Visualize Data
5. Correlation Analysis
6. Prepare Features and Labels
7. Train-Test Split
8. Train Random Forest Model
9. Evaluate Accuracy
10. Predict Wine Quality

---

## Installation

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

## Run the Project

```bash
jupyter notebook
```

Open:

```bash
wine_quality_prediction.ipynb
```

---

## Model Performance

Test Accuracy: ~90–95%

*(Accuracy may vary depending on train-test split.)*

---

## Future Improvements

- Hyperparameter Tuning
- Cross Validation
- XGBoost
- Feature Importance Analysis
- Streamlit Web App
- Flask API Deployment



