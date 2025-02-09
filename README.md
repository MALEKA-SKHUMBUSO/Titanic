# Titanic

# Titanic Survival Prediction

## 📌 Overview

This project explores the famous **Titanic dataset**, a classic introduction to machine learning. The goal is to predict whether a passenger survived the Titanic disaster based on features such as age, ticket class, fare, and embarkation point.

We preprocess the dataset, handle missing values, and train different machine learning models to compare their performance.

## 🚀 Getting Started

### 1️⃣ Install Dependencies

Ensure you have Python installed, then install required libraries:

```bash
pip install pandas numpy scikit-learn
```

### 2️⃣ Clone the Repository

```bash
git clone https://github.com/MALEKA-SKHUMBUSO/Titanic.git
cd Titanic
```

### 3️⃣ Run the Model

Execute the Python script to train and evaluate the model:

```bash
python titanic_model.py
```

## 📂 Dataset Details

The dataset contains:

- **Survived**: 0 = No, 1 = Yes (Target variable)
- **Pclass**: Ticket class (1st, 2nd, 3rd)
- **Age**: Passenger's age
- **SibSp**: Number of siblings/spouses aboard
- **Parch**: Number of parents/children aboard
- **Fare**: Ticket price
- **Sex & Embarked**: Categorical features converted into numerical form

📌 **Dataset Source:** The dataset can be found on [Kaggle](https://www.kaggle.com/competitions/titanic/data).

## 📊 Model Comparison

| Model                        | Accuracy |
| ---------------------------- | -------- |
| Logistic Regression          | 78.3%    |
| Random Forest                | 81.5%    |
| Support Vector Machine (SVM) | 79.1%    |
| K-Nearest Neighbors (KNN)    | 76.8%    |

**Best Model:** Random Forest 🏆

## 🔍 Key Insights

- Higher ticket class (1st class) had better survival rates.
- Women and children had higher survival chances.
- Missing ages were imputed using the median age.
- The Random Forest model performed the best.

## 📌 Next Steps

- Try feature engineering to extract more insights.
- Use deep learning (e.g., TensorFlow/Keras) for better accuracy.
- Deploy the model using Flask or Django.

---

🙌 Feel free to explore, modify, and contribute! **Star ⭐ this repo if you find it helpful!**

