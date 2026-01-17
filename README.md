# titanic-kaggle-compition-submission
my best submission for titanic compition

# Titanic Survival Prediction (Kaggle)

This repository contains my solution for the **Kaggle Titanic: Machine Learning from Disaster** competition.

The goal of this project is to predict whether a passenger survived the Titanic disaster based on available passenger data such as age, gender, passenger class, and family information.

---

## 📊 Dataset
- Source: Kaggle Titanic Competition
- Files used:
  - `train.csv` – training data with survival labels
  - `test.csv` – test data without labels

---

## ⚙️ Approach

### Data Preprocessing
- Handled missing values for Age, Fare, and Embarked
- Encoded categorical variables such as Sex and Embarked
- Removed irrelevant columns like Name, Ticket, and Cabin

### Feature Engineering
- Extracted passenger titles (Mr, Mrs, Miss, etc.) from names
- Created family-based features such as `FamilySize` and `IsAlone`
- Used both raw and engineered features to improve prediction accuracy

### Model Used
- Random Forest / Gradient Boosting Classifier
- Chosen for its ability to capture non-linear patterns in the data

---

## 📈 Results
- Achieved approximately **0.80+ accuracy** on the Kaggle public leaderboard
- Demonstrates effective feature engineering and model selection

---

## 📁 Files in this Repository
- `submission.csv` – Final prediction file submitted to Kaggle
- `titanic_model.ipynb` (optional) – Notebook containing the full workflow
- `README.md` – Project overview and explanation

---

## 🧠 Key Learnings
- Importance of data preprocessing and handling missing values
- Feature engineering significantly impacts model performance
- Simple ensemble models perform well on structured datasets

---

## 🔗 Kaggle Competition Link
https://www.kaggle.com/competitions/titanic

---

## 🔗 Competition Notebook Link
https://www.kaggle.com/code/shetyerahul/titanic-submission

## 👤 Author
Rahul Shetye
