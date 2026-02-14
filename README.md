

#  End-to-End Machine Learning Pipeline



##  Overview

This task demonstrates an **end-to-end Machine Learning pipeline** using the **Breast Cancer Dataset (sklearn)**.
The goal is to build a complete workflow including preprocessing, model training, evaluation, and saving the trained model.

---

##  Dataset

* **Primary Dataset:** Breast Cancer Dataset (from sklearn)
* Type: Binary Classification
* Target:

  * `0` → Malignant
  * `1` → Benign

---

##  Tools & Technologies

* Python
* Pandas
* NumPy
* Scikit-learn
* Jupyter Notebook / Google Colab

---

## ML Pipeline Steps

1. Load dataset
2. Separate features and target
3. Apply preprocessing using `ColumnTransformer`
4. Scale numerical features using `StandardScaler`
5. Build ML pipeline using `Pipeline`
6. Split data into train and test sets
7. Train Logistic Regression model
8. Evaluate using:

   * Accuracy
   * Precision
   * Recall
   * F1-score
9. Save trained model as `.pkl` file

---

##  Evaluation Metrics

* **Accuracy** – Overall correctness
* **Precision** – Correct positive predictions
* **Recall** – Ability to detect actual positives
* **F1 Score** – Balance between precision and recall

---

##  Model Saving

The trained pipeline is saved using `joblib` as:

```
breast_cancer_pipeline.pkl
```







