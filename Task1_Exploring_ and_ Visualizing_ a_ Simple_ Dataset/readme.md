# Task: Iris Dataset Visualization and Analysis 🌸

## 📌 Objective:
The aim of this task was to explore and visualize the famous Iris dataset. The focus was on understanding the relationships between different flower measurements (sepal and petal) and their species using various plots. No machine learning model was applied in this task — it's purely for **data visualization and basic statistical understanding**.

---

## 📊 Dataset Used:
- **Dataset**: Iris Dataset
- **Source**: Built-in dataset from the `seaborn` library
- **Shape**: 150 rows × 5 columns
- **Target Variable**: `species` (Setosa, Versicolor, Virginica)
- **Features**:
  - `sepal_length`
  - `sepal_width`
  - `petal_length`
  - `petal_width`

---

## 📈 What I Did:
- Imported required libraries: `pandas`, `seaborn`, and `matplotlib`
- Loaded the dataset using `sns.load_dataset("iris")`
- Displayed:
  - Shape and column names
  - First five rows
  - Summary info and descriptive statistics

### 📊 Visualizations:
1. **Scatter Plots**:
   - Sepal length vs Sepal width (colored by species)
   - Petal length vs Petal width (colored by species)
2. **Histogram**:
   - Distribution of all numerical features
3. **Box Plots**:
   - For detecting outliers in all numeric columns



## 🔍 Key Findings:
- Each species shows clear separation in the **petal measurements**, especially petal length and width.
- **Setosa** is most distinct, while **Versicolor and Virginica** slightly overlap in sepal size.
- Box plots helped visualize the spread of data and detect any **potential outliers**.



## 🧾 Additional Notes:
- This task focuses on **Exploratory Data Analysis (EDA)** only — no model training or prediction is involved.
- The notebook is commented and structured in clear sections for better understanding.
- You can run this notebook on **Google Colab** or Jupyter Notebook.


