# ⚽ Premier League Match Prediction using Machine Learning

This project focuses on predicting English Premier League (EPL) match outcomes using historical football statistics and machine learning models.

The objective is to classify match results into three categories:

- Home Win (H)
- Draw (D)
- Away Win (A)

---

## 📌 Project Overview

Football match prediction is a challenging multi-class classification problem because match outcomes depend on team form, historical performance, home advantage, momentum, and many hidden factors.

This project builds a complete machine learning pipeline including:

- Data preprocessing
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Model Training
- Model Comparison
- Advanced Ensemble Learning

---

## 📂 Dataset

This project uses English Premier League historical datasets from multiple seasons:

- 2017–18
- 2018–19
- 2019–20
- 2020–21
- 2021–22

Additional final dataset is included for evaluation.

Dataset contains:

- Match statistics
- Goals scored
- Shots / shots on target
- Team names
- Betting odds
- Full-time result (target variable)

Target variable:

```python
FTR:
H = Home Win
D = Draw
A = Away Win
```

---

## 🛠 Technologies & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- LightGBM
- Google Colab

---

## ⚙️ Feature Engineering

Custom leakage-free features were created to improve prediction quality:

- Rolling goals scored (last 3 / 5 matches)
- Rolling goals conceded
- Team form points
- Win streaks
- Draw rates
- Venue-specific performance
- Head-to-head statistics
- Goal difference
- Home advantage
- Rolling shots on target

These features capture recent team momentum and historical matchup behavior.

---

## 🤖 Machine Learning Models

Baseline models:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Naive Bayes
- Support Vector Machine (SVM)
- Neural Network (MLP)

Advanced models:

- XGBoost
- LightGBM
- Stacking Ensemble

---

## 📊 Results

Performance Summary:

| Model | Accuracy |
|------|----------|
| Logistic Regression | ~64–68% |
| KNN | ~64–69% |
| Naive Bayes | ~63–67% |
| SVM | ~69–71% |
| Neural Network | ~70–71% |
| XGBoost | ~75–78% |
| LightGBM | ~75–78% |
| Stacking Ensemble | ~80% |

Best model:

🏆 **Stacking Ensemble (~80% Accuracy)**

---

## 🔍 Key Insights

- Recent team form strongly affects predictions
- Home advantage matters but contributes less than rolling form
- Draw outcomes remain hardest to predict
- Ensemble models outperform classical ML algorithms

---

## 📈 Visualizations Included

This repository includes:

- Target distribution plots
- Correlation heatmaps
- Model comparison charts
- Confusion matrices
- Feature importance graphs

---

## 📄 Research Report

A complete research-style project report (IEEE-style) is included in this repository.

---

## 🚀 Future Improvements

Possible improvements:

- Add more historical seasons
- Include player-level statistics
- Injury and squad rotation features
- Betting simulation system
- Deep learning (LSTM / Transformer)

---

## 👩‍💻 Author

Haleema Amjad
Computer Science Student  
Machine Learning Enthusiast
