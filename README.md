# Logistic-Regression-and-Random-Forest-with-10-Fold-Cross-Validation-evaluation
Classification project using Logistic Regression and Random Forest with 10-Fold Cross-Validation evaluation.



# Classification with Logistic Regression and Random Forest

This repository showcases a binary/multi-class classification workflow implemented in Python. The project evaluates and compares the baseline performance of **Logistic Regression** against a **Random Forest Classifier**, utilizing robust validation techniques to ensure model generalizability.

### Tech Stack & Libraries
* **Language:** Python
* **Data Exploration:** Pandas, NumPy, Matplotlib, Seaborn
* **Machine Learning:** Scikit-learn (`LogisticRegression`, `RandomForestClassifier`)
* **Model Validation:** `cross_val_score` (10-Fold Cross-Validation), Confusion Matrix, Classification Report

### Validation & Performance Highlights
* **Algorithm Comparison:** Explored the analytical trade-offs between linear decision boundaries (Logistic Regression) and ensemble tree methodologies (Random Forest).
* **10-Fold Cross-Validation:** Verified the Random Forest model using a 10-fold split strategy, yielding a robust mean cross-validation accuracy of **95.19%** with an exceptionally low standard deviation (~0.003), confirming that the model is well-generalized and resilient against overfitting.
