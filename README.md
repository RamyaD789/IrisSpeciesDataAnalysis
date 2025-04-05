# 🌸 Iris Species EDA & Statistical Analysis

This project explores the classic **Iris dataset** using data visualization and statistical techniques to distinguish between the three species: *Setosa*, *Versicolor*, and *Virginica*.

## 📌 Objective
- Perform Exploratory Data Analysis (EDA) to identify patterns between the species.
- Use visualizations to highlight how features like petal and sepal measurements vary.
- Apply statistical hypothesis testing to validate if differences between species are significant.

---

## 📊 Dataset Information
The Iris dataset contains 150 observations of iris flowers from three species:
- **Features**: `sepal length`, `sepal width`, `petal length`, `petal width`
- **Target**: `species`

---

## 📈 What I Did

### 1️⃣ Data Preparation
- Loaded the dataset using `pandas`
- Checked for null values and basic info

### 2️⃣ Visual Analysis
- Created **pairplots** to visualize feature distribution by species
- Used **histograms** to compare overlaps in petal and sepal measurements

### 3️⃣ Key Insight from Plots
- *Setosa* is clearly distinguishable from the other two species
- **Petal length** and **petal width** are more effective at separating *Versicolor* and *Virginica* compared to sepal features

### 4️⃣ Statistical Testing
- Performed **t-tests** between *Versicolor* and *Virginica* for:
  - Petal Length
  - Petal Width
- Result: Very low p-values (p < 0.05), confirming a significant difference between these species for both features

### 5️⃣ Simple Logistic Regression
- Built a logistic regression model using **scikit-learn** to distinguish between Versicolor and Virginica
- Achieved **95% accuracy** with confusion matrix analysis

---

## 🧰 Tools & Libraries
- `pandas`, `numpy` – data manipulation
- `seaborn`, `matplotlib` – data visualization
- `scipy` – statistical hypothesis testing
- `sklearn` – logistic regression modeling

---

## 📌 Conclusion
This analysis confirms that **petal measurements** (especially length & width) are the best parameters for species classification. *Setosa* is easily separable, while *Versicolor* and *Virginica* require deeper analysis like hypothesis testing and modeling.

---

