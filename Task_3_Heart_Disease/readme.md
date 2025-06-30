# Task 3: Heart Disease Prediction using Logistic Regression 

##  Objective:
The main goal of this task was to build a classification model that can predict whether a person is at risk of heart disease using the **UCI Heart Disease dataset**. The problem was solved as a **binary classification** task (disease or no disease) using **Logistic Regression**.

---

##  Dataset Used:
- **Name**: Heart Disease UCI Dataset
- **Source**: [UCI Repository / Kaggle]
- **Shape**: Varies (depends on preprocessing), generally ~300 rows and 14+ columns
- **Target**: `num` column (converted to binary: `0 = No Disease`, `1 = Disease`)
- Features include:
  - Age, sex, chest pain type, resting BP, cholesterol, fasting blood sugar, etc.

---

##  What I Did:

### 1. Data Loading & Preprocessing
- Loaded dataset using `pandas`.
- Checked and filled **missing values** using column mean.
- Converted the `num` column to a new `target` column for binary classification.
- Used one-hot encoding for categorical variables.

### 2. Exploratory Data Analysis (EDA)
- Plotted the distribution of heart disease cases using `countplot`.
- Visualized feature correlations using a **heatmap**.
- Mapped gender to numeric format (`Male = 1`, `Female = 0`).

### 3. Model Training
- Split the data using `train_test_split` (80/20).
- Trained a **Logistic Regression** model using `sklearn`.

### 4. Evaluation Metrics
- **Accuracy Score**
- **Confusion Matrix**
- **ROC Curve and AUC Score**

### 5. Feature Importance
- Visualized model coefficients to see which features contribute most to predictions.

---

  Key Results:
- **Model Accuracy**: ~85% (may vary slightly depending on the run)
- ROC Curve shows a good separation between positive and negative classes.
- Important features included: `cp` (chest pain), `thalach` (max heart rate), `oldpeak`, etc.

