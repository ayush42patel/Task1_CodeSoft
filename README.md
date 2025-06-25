# Task1_CodeSoft
Machine learning model to predict Titanic survival using Python
# 🚢 Titanic Survival Prediction - Machine Learning Project

https://colab.research.google.com/drive/1kxq1kqqG9Dxpz4R1ZirhAcBYi91WVwQO?usp=sharing

This project predicts whether a passenger survived the Titanic disaster using machine learning (Random Forest Classifier). It is part of a Data Science internship task and is beginner-friendly.

---

## 📁 Files

| File | Description |
|------|-------------|
| `titanic_survival_prediction.ipynb` | Complete Colab notebook with code and explanations |
| `Titanic-Dataset.csv` *(optional)* | Dataset used (you can upload if under 100MB) |
| `README.md` | Project overview |

---

## 📊 Technologies Used

- Python
- Google Colab
- pandas, numpy, seaborn, matplotlib
- scikit-learn (RandomForestClassifier)

---

## 🚀 How to Run the Project

1. Click the **"Open in Colab"** badge above.
2. Upload the dataset (`Titanic-Dataset.csv`) when prompted.
3. Run each cell step-by-step to:
   - Explore and clean the data
   - Train a machine learning model
   - Predict survival
   - Evaluate performance

---

## 🧠 Model Used

- **Random Forest Classifier**  
A powerful ensemble method that builds multiple decision trees and combines them for accurate classification.

---

## 🧪 Example Prediction

```python
predict_survival(1, 0, 29, 0, 0, 100, 0)
# Output: ✅ Survived
