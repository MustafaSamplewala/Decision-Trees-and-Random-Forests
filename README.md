# Decision-Trees-and-Random-Forests

This project is part of the **AI & ML Internship**, focusing on tree-based models for classification using the **Heart Disease Dataset**.

---

## 🔍 Objective

- Learn how to build and evaluate **Decision Trees** and **Random Forests**.
- Understand concepts like **overfitting**, **cross-validation**, and **feature importance**.
- Visualize decision trees and analyze model performance.

---

## 📁 Dataset

- **Name**: Heart Disease Dataset
- **File**: `heart.csv`
- **Target column**: `target` (0 = No disease, 1 = Disease)

---

## 🧪 Tools & Libraries

- Python
- Scikit-learn
- Matplotlib, Seaborn
- Pandas, NumPy

---

## 📌 Tasks Performed

### ✅ 1. Train a Decision Tree Classifier
- Used `DecisionTreeClassifier` from `sklearn`.
- Evaluated accuracy and classification report.

### ✅ 2. Visualize the Tree
- Plotted the decision tree using `plot_tree`.

### ✅ 3. Analyze Overfitting
- Plotted training vs. testing accuracy for different tree depths.

### ✅ 4. Train a Random Forest
- Used `RandomForestClassifier` for ensemble learning.
- Compared performance against a single decision tree.

### ✅ 5. Interpret Feature Importances
- Extracted and plotted feature importances from the random forest model.

### ✅ 6. Evaluate using Cross-Validation
- Performed 5-fold cross-validation for both models.

---

## 📊 Results Summary

| Model            | Accuracy (Test Set) | Cross-Validation Accuracy |
|------------------|---------------------|----------------------------|
| Decision Tree    | 98.54%              | 100.00%                    |
| Random Forest    | 98.54%              | 99.71%                     |


---

## 📷 Visuals

- 📌 Decision Tree Plot
- 📌 Accuracy vs. Depth Curve
- 📌 Feature Importance Bar Chart

---


