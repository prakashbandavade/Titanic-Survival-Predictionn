# codsoft internship task
# 🚢 Titanic Survival Prediction

A machine learning project to predict passenger survival on the Titanic using data analysis, feature engineering, and classification algorithms.

## 📚 Overview

This project uses the Titanic dataset to build a predictive model that determines whether a passenger survived the Titanic shipwreck. It involves:

- Exploratory data analysis (EDA)
- Data preprocessing and feature engineering
- Model selection and training
- Performance evaluation

The dataset was originally provided by [Kaggle's Titanic Competition](https://www.kaggle.com/c/titanic).

## 🧠 Problem Statement

Using information such as age, sex, ticket class, and more, predict whether a given passenger survived the disaster.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib & Seaborn (for data visualization)
- Scikit-learn (for modeling)
- Jupyter Notebook

## 📁 Project Structure

titanic-survival-prediction/
│
├── data/ # Dataset files (train.csv, test.csv)
├── notebooks/ # Jupyter notebooks
│ └── titanic_analysis.ipynb
├── models/ # Saved models (if any)
├── src/ # Scripts for data processing and modeling
│ ├── data_preprocessing.py
│ ├── model_training.py
│ └── predict.py
├── outputs/ # Output files (plots, predictions, etc.)
├── README.md # Project readme
└── requirements.txt # Dependencies

markdown
Copy
Edit

## 🔍 Exploratory Data Analysis

- Distribution of survival by gender, age, class, etc.
- Handling missing data (e.g., Age, Cabin, Embarked)
- Visualizations for better insight

## ⚙️ Feature Engineering

- Creating new features like `FamilySize`, `Title`, `IsAlone`
- Converting categorical variables into numeric (One-Hot Encoding or Label Encoding)

## 🧪 Model Training

Algorithms used:

- Logistic Regression
- Random Forest
- Support Vector Machine
- K-Nearest Neighbors
- XGBoost

Performance evaluated using:

- Accuracy
- Confusion Matrix
- Cross-validation

## ✅ Results

| Model               | Accuracy |
|--------------------|----------|
| Logistic Regression| 80.3%    |
| Random Forest      | 83.2%    |
| XGBoost            | 84.1%    |

> *Note: These results may vary based on hyperparameters and preprocessing methods.*

## 📊 Visualization Examples

- Survival rate by gender and class
- Correlation heatmaps
- Age and fare distribution

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/titanic-survival-prediction.git
   cd titanic-survival-prediction
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Run the notebook:

bash
Copy
Edit
jupyter notebook notebooks/titanic_analysis.ipynb
📦 Dataset
Download the Titanic dataset from Kaggle and place train.csv and test.csv in the data/ directory.

🤝 Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
