
# Iris-Flower-Classification


---

# 🌸 Iris Flower Classification

### Random Forest Machine Learning Project

---

## 🌿 Project Overview

This project implements a structured machine learning workflow to classify Iris flower species using a **Random Forest Classifier**.

The approach follows a disciplined data science process:

* Data import and inspection
* Data cleaning and validation
* Exploratory Data Analysis (EDA)
* Correlation analysis
* Model training and evaluation

The objective was to build a reliable classification model while understanding the dataset through meaningful visualization and structured analysis.

---

# 📊 Dataset Summary

The dataset contains **150 flower observations**, each described by four numerical measurements:

* Sepal Length
* Sepal Width
* Petal Length
* Petal Width

Target classes:

* Setosa
* Versicolor
* Virginica

The dataset is perfectly balanced across all three species.


---

# 🔎 Data Preparation & Cleaning

After importing the dataset from CSV:

* Dataset structure was inspected
* Statistical summaries were reviewed
* Missing values were checked
* Duplicate records were verified

✔ No missing values
✔ No duplicate entries

The `Id` column was removed since it does not contribute to prediction.

The dataset required no additional preprocessing, confirming high data quality.

---

# 📈 Exploratory Data Analysis (EDA)

EDA was performed before modeling to understand distribution, balance, and feature relationships.

---

## 🌼 Species Distribution

Each species appears exactly 50 times.

✔ Balanced dataset
✔ No class imbalance
<img width="562" height="455" alt="output 1 IRIS" src="https://github.com/user-attachments/assets/3caa0bb1-4f47-4718-aab1-91f2db755c24" />
---

## 📦 Feature Spread & Outlier Detection
<img width="658" height="528" alt="IRIS 2" src="https://github.com/user-attachments/assets/06fb75cf-3e4c-43a0-8d96-148e4153f3ec" />

Boxplots revealed:

* No extreme outliers
* Stable feature ranges
* Clear separation in petal measurements

The dataset is clean and well-behaved.

---

## 🔗 Correlation Analysis
<img width="637" height="528" alt="IRIS 3" src="https://github.com/user-attachments/assets/83983587-41bd-425d-9f59-10fdcc89185a" />

The correlation matrix revealed:

* Strong positive correlation between Petal Length and Petal Width
* Moderate correlation between Sepal Length and Petal Length
* Weaker correlations involving Sepal Width

This indicates that petal features carry the strongest predictive signal.

---

# 🌳 Model Development

After completing EDA, the Iris dataset was loaded using Scikit-learn’s built-in dataset utility.

* Features and target variable were separated
* Data split into 80% training and 20% testing
* Random state fixed at 40 for reproducibility

A **Random Forest Classifier** was trained on the training data and evaluated on unseen test data.

---

# 📈 Model Evaluation

The trained model was evaluated using:

* Accuracy Score
* Precision
* Recall
* F1-Score

The classifier achieved perfect performance on the testing dataset, correctly classifying all samples in the evaluation split.

This strong result aligns with:

* Clean and balanced dataset
* Clear class separability (especially Setosa)
* Strong predictive power of petal measurements

---

# 🌟 Project Highlights

✔ Clean dataset with zero preprocessing complexity
✔ Balanced target classes
✔ Insight-driven EDA
✔ Reproducible train-test split
✔ Strong model performance

---

# 🧠 What This Project Demonstrates

* Structured machine learning workflow
* Data validation best practices
* Effective visualization for insight extraction
* Reliable supervised classification
* Alignment between EDA findings and model performance

---

# 🌸 Final Reflection

This project demonstrates how disciplined data inspection, visualization, and modeling lead to accurate and interpretable results.

By understanding feature relationships before training the model, the classification outcome becomes both predictable and explainable.



Tell me the direction you prefer.
