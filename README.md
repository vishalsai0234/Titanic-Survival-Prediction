# Titanic Survival Prediction 🚢

This project builds a machine learning model to predict whether a passenger survived the Titanic disaster.

## 📁 Project Structure
- 01_eda.ipynb                # Exploratory Data Analysis 
- 02_preprocessing.ipynb      # Data cleaning & feature engineering 
- 03_model_building.ipynb     # Model selection and training 
- 04_model_performance.ipynb  # Evaluation metrics 
- requirements.txt            # List of dependencies
- tested_preprocessed.csv     # Preprocessed dataset for building machine learning models
- README.md                   # Project overview, methods, results

## 📊 Dataset

The dataset includes features like:

- Passenger class (`Pclass`)
- Sex
- Age
- Siblings/spouses aboard (`SibSp`)
- Parents/children aboard (`Parch`)
- Fare
- Embarkation port (`Embarked`)

## 🧹 Preprocessing

- Handled missing values (`Age`, `Embarked`, `Fare`)
- Encoded categorical variables
- Normalized numerical features
- Dropped irrelevant columns (`Name`, `Ticket`, `Cabin`, etc.)

## 🤖 Model

- Used `Logistic Regression`, `Random Forest`, and `Decision Tree`
- Evaluated on **Accuracy**, **Precision**, **Recall**, and **F1-score**

## 📈 Results

Final model performance:

| Metric     | Score |
|------------|-------|
| Accuracy   |  1.0  |
| Precision  |  1.0  |
| Recall     |  1.0  |
| F1 Score   |  1.0  |

## 🚀 Getting Started

Install dependencies:

```bash
pip install -r requirements.txt
```
Then run the notebooks in order to reproduce results.
