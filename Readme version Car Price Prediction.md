# 🚗 Car Price Prediction — Linear Regression

![Project Banner](https://img.shields.io/badge/Car%20Price%20Prediction-Linear%20Regression-0A66C2?style=for-the-badge\&logo=python\&logoColor=white)



```
📦 Data → 🔎 Explore → 🔧 Prepare → ✂️ Split → 📈 Train → 📊 Evaluate → 🔮 Predict
```

---

# 📊 Model Visualization

A linear regression model learns a straight‑line relationship between vehicle attributes and selling price.

---

# 📦 Data Import

🧰 Libraries for data handling, visualization, and ML loaded
📂 Used‑car dataset read into structured table (DataFrame)

✔️ Rows → individual cars
✔️ Columns → vehicle attributes

---

# 🔎 Data Exploration

📏 Verified dataset dimensions (rows & columns)
📐 Confirmed dataset shape consistency
🧾 Inspected column types and non‑null counts
🚫 Checked missing values → **none detected**

Outcome:

```
Clean, structured dataset ready for modeling
```

---

# 📊 Categorical Analysis

Frequency distribution examined for:

* Fuel_Type
* Seller_Type
* Transmission
* Owner

Purpose:

✔️ Category balance
✔️ Data realism
✔️ Encoding readiness

---

# 🔧 Feature Engineering

Categorical → numeric encoding applied:

```
Fuel: Petrol 0 | Diesel 1 | CNG 2
Seller: Dealer 0 | Individual 1
Transmission: Manual 0 | Automatic 1
```

Result:

```
All features numeric → ML‑compatible dataset
```

---

# ✂️ Feature / Target Split

🎯 Target:

```
Selling_Price
```

📊 Features:

```
Vehicle attributes excluding Car_Name
```

---

# 🧪 Train–Test Partition

Dataset divided into:

* 🟦 Training set
* 🟩 Testing set

Ensures unbiased performance evaluation on unseen cars.

---

# 📈 Model Training

Algorithm:

```
Linear Regression
```

Learned relationship:

```
Vehicle characteristics → Market selling price
```

---

# 📊 Model Performance (Test Data)

**R² Score:**

```
0.8401415675614679
```

**Interpretation:**

* ≈84% of price variance explained by features
* Strong linear relationship captured
* Good generalization on unseen vehicles
* Residual variance likely from market factors (brand perception, condition, region)

✔️ Reliable predictive capability for resale pricing scenarios

---

# 📉 Prediction Validation

Actual vs Predicted price comparison:

✔️ Points concentrated near diagonal
✔️ Low dispersion around trend line
✔️ Consistent prediction accuracy across range

Indicates stable regression fit.

---

# 🔮 Price Prediction

Model applied to unseen test vehicles.

Output:

```
Estimated selling prices
```

Demonstrates applied machine learning for automotive price estimation.

---

# 🌍 Practical Relevance

Linear regression applied to structured vehicle data enables:

* Used‑car valuation tools
* Dealer pricing support
* Marketplace price guidance
* Residual value estimation
* Data‑driven negotiation benchmarks

---

# 🧠 Capability Demonstrated

✔️ Data validation & preparation
✔️ Feature encoding
✔️ Regression modeling
✔️ Quantitative evaluation
✔️ Predictive analytics interpretation

