# 👤 Gender Classification using Machine Learning

This project applies various supervised machine learning models to classify gender based on a given dataset. It demonstrates data preprocessing, model training, and evaluation using multiple algorithms.

---

## 📁 Files Included

- `gender_classification.ipynb` — Main Jupyter Notebook with the full ML pipeline
- `README.md` — Project documentation

*(Add your dataset file if it’s small, or link it if large)*

---

## 📌 Key Highlights

- ✅ Preprocessing with Label Encoding, Ordinal Encoding, and Feature Scaling
- ✅ Trained multiple ML classifiers:
  - Logistic Regression
  - K-Nearest Neighbors (KNN)
  - Decision Tree
  - Random Forest
  - Support Vector Machine (SVM)
  - Gradient Boosting Classifier
- ✅ Model evaluation with:
  - Accuracy Score
  - Confusion Matrix
  - Classification Report
- ✅ Visualizations using Matplotlib and Seaborn
- ✅ Decision Tree visualized with Graphviz

---

## 🧠 ML Workflow

1. **Import Libraries & Load Data**
2. **Data Cleaning & Preprocessing**
   - Handle missing values
   - Encode categorical variables
   - Normalize/scale features
3. **Split Dataset** into train/test sets using `train_test_split`
4. **Train ML Models**
   - Fit and predict using 6 different algorithms
5. **Evaluate Performance**
   - Use `accuracy_score`, `confusion_matrix`, and `classification_report`
6. **Visualizations**
   - Heatmaps of confusion matrices
   - Graphviz tree visualization

---

## 📊 Accuracy Comparison (sample format)

| Model                  | Accuracy |
|------------------------|----------|
| Logistic Regression    | 95.0%    |
| K-Nearest Neighbors    | 94.2%    |
| Decision Tree          | 96.1%    |
| Random Forest          | 97.4%    |
| Support Vector Machine | 96.8%    |
| Gradient Boosting      | 98.0%    |

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/gender-classification-ml.git
   cd gender-classification-ml
2. jupyter notebook gender_classification.ipynb
3. Run all cell in order
