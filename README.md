# DataCamp Associate Data Scientist: Practical Exam (House Sales)

> **Note:** This repository contains my solution code for the **DataCamp Associate Data Scientist Practical Exam**. As one of my early projects in Python, it reflects my learning journey through data cleaning, exploratory data analysis, and predictive modeling. While the codebase is structured for a specific certification prompt, it represents a foundational milestone in my applied data science skills.

---

## 🏢 Business Context & Objective
**RealAgents** is a real estate agency focusing on metropolitan housing sales. To stay competitive and decrease the time-to-sale (often caused by overpricing properties), the company wanted to **optimize listing prices** by accurately predicting sale prices based on house characteristics.

---

## 🛠️ Project Tasks & Workflow

The solution is divided into 5 sequential tasks reflecting a real-world data science pipeline:

1. **Task 1: Exploratory Data Analysis (EDA)**
   * Investigated missing values in the dataset, specifically analyzing the `city` column to identify data collection gaps.

2. **Task 2: Data Cleaning & Preprocessing**
   * Built a robust data-cleaning pipeline to handle missing values using domain-appropriate strategies (e.g., filling numerical columns with means, categorical with modes or custom tags like `"Unknown"`).
   * Standardized text data (e.g., cleaning area strings) and set up correct data types and ordinal categories for `house_type`.

3. **Task 3: Statistical Aggregation**
   * Investigated the team's hypothesis that the number of bedrooms is the primary driver of house prices.
   * Calculated the average sale price and variance grouped by the number of bedrooms.

4. **Task 4: Baseline Predictive Model**
   * Implemented a baseline **Linear Regression** model using `scikit-learn`.
   * Performed feature engineering by extracting temporal features (year, month, day) from `sale_date` and applying one-hot encoding (`pd.get_dummies`) to categorical features (`city`, `house_type`).
   * Generated price predictions on unseen validation data.

5. **Task 5: Comparison Predictive Model**
   * Built an advanced comparison model using a **Random Forest Regressor** to capture non-linear relationships and interactions between features, improving upon the baseline model's performance.

---

## 🚀 Key Skills & Learnings Acquired

* 🧹 **Data Cleaning & Imputation:** Handling messy, real-world datasets with missing values, string manipulations, and type conversions.
* 📊 **Exploratory Data Analysis (EDA):** Grouping, aggregating, and extracting statistical insights (mean, variance) to answer specific business questions.
* ⚙️ **Feature Engineering:** Extracting datetime attributes and encoding categorical variables for machine learning models.
* 🤖 **Supervised Machine Learning:** Training, evaluating, and comparing models (`LinearRegression` vs. `RandomForestRegressor`) using `scikit-learn`.

---

## 🛠️ Tech Stack

* **Language:** Python
* **Data Manipulation & Analysis:** Pandas, NumPy
* **Machine Learning:** Scikit-Learn (`LinearRegression`, `RandomForestRegressor`)

---
