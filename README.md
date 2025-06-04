# ❤️ Heart Disease Prediction using Decision Trees & Random Forests

## 📌 Objective

To build and evaluate classification models using **Decision Tree** and **Random Forest** classifiers to predict the presence of heart disease in patients using the UCI Heart Disease dataset.

---

## 🛠️ Tools & Libraries

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Graphviz / `plot_tree` (for visualization)

---

## 🔢 Dataset Overview

- Source: UCI Heart Disease Dataset  
- Target variable: `target` (0 = no heart disease, 1 = heart disease)
- Total attributes used: 14
- Some categorical features (`cp`, `thal`, `slope`) are one-hot encoded

---

## ✅ Steps Performed

### 1. **Preprocessing**
- Handled categorical features with `pd.get_dummies`
- Normalized/cleaned data as needed

### 2. **Decision Tree Classifier**
- Trained with different depths
- Analyzed **overfitting vs underfitting**
- Selected optimal `max_depth = 8`
- Visualized the tree

### 3. **Random Forest Classifier**
- Trained a model with 100 estimators
- Compared accuracy with Decision Tree

### 4. **Feature Importance**
- Plotted top features from Random Forest

### 5. **Cross-Validation**
- Used 5-fold CV to evaluate generalization
- Results:
  - **Decision Tree CV Accuracy**: 0.982 ± 0.013
  - **Random Forest CV Accuracy**: 0.994 ± 0.007

---

## 📊 Conclusion

- **Random Forest outperformed** the Decision Tree in terms of accuracy and consistency.
- The model is effective for predicting heart disease and can be extended further with hyperparameter tuning and more robust validation.

---

## 📎 Folder Structure

