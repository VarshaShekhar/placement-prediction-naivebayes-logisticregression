# 🎓 Placement Prediction using Naïve Bayes and Logistic Regression

This project aims to predict student placement outcomes (Placed or NotPlaced) based on academic performance, aptitude scores, and co-curricular factors. Two machine learning classifiers — **Naïve Bayes** and **Logistic Regression** — were implemented and compared.

---

## 📁 Dataset

- **File:** `placementdata.csv`
- **Samples:** 10,000 student records
- **Target Variable:** `PlacementStatus` (`Placed` or `NotPlaced`)
- **Features:**
  - CGPA
  - Internships
  - Projects
  - Workshops/Certifications
  - AptitudeTestScore
  - SoftSkillsRating
  - ExtracurricularActivities
  - PlacementTraining
  - SSC_Marks
  - HSC_Marks

---

## 🛠️ Technologies Used

- Python
- Scikit-learn
- Imbalanced-learn (`SMOTE`)
- Seaborn & Matplotlib
- Pandas & NumPy
- Jupyter Notebook

---

## 📊 Models Implemented

1. **Gaussian Naïve Bayes**
2. **Logistic Regression**

Each model was trained and evaluated using:
- Train/Test split (80/20)
- SMOTE for class imbalance
- Stratified K-Fold Cross Validation
- Grid Search with hyperparameter tuning
- Pipelines for cleaner workflow

---

## 📈 Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- ROC Curve & AUC Score

---

## ✅ Results Summary

| Metric     | Logistic Regression | Naïve Bayes |
|------------|---------------------|-------------|
| Accuracy   | 79.75%              | 79.85%      |
| F1-Score   | 0.7726              | 0.7698      |
| AUC Score  | ~0.87               | ~0.86       |

- Logistic Regression showed slightly better recall and F1-score.
- Naïve Bayes was faster and slightly better on precision.
- Both models performed comparably on ROC-AUC.

---

## 📌 Conclusion

- **Logistic Regression** is preferred for interpretability and better recall.
- **Naïve Bayes** is a fast, lightweight baseline especially useful when features are independent or the dataset is large.
- F1-score was prioritized over accuracy due to class imbalance (58% NotPlaced vs. 42% Placed).

---

## 📂 Files Included

- `placement_NaiveBayes_LogisticRegression.ipynb` – Complete notebook with code, visuals, and analysis
- 'placement_NaiveBayes_LogisticRegression.html'
- `placementdata.csv` – Dataset
- `README.md` – Project overview

---

## 🧠 Future Improvements

- Try ensemble models (e.g., Random Forest, XGBoost)
- Perform feature selection
- Use advanced sampling techniques (e.g., SMOTE + Tomek links)
- Deploy as a web app using Streamlit or Flask

---

## 🤝 Connect

- [LinkedIn](https://www.linkedin.com/in/varsha-shekhar)
- [Gmail](varshaiyer96@gmail.com)
