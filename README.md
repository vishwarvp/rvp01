1. 📊 Exploratory Data Analysis (EDA) Projects Portfolio

This repository contains **three complete Exploratory Data Analysis (EDA) projects**, created using a **structured, industry-standard data analysis workflow**.
Each project follows the same **12-step EDA process** to ensure clean, reliable, and meaningful insights.

2. 🗂️ Projects Included

    1. Titanic Dataset EDA
    2. Taxi Data Analysis
    3. MPG (Mileage per Gallon) Dataset EDA

Each project includes:
    
    1. Data loading
    2. Data cleaning
    3. Data visualization
    4. Feature engineering
    5. Final clean dataset export

3. ✅ Standard EDA Workflow Followed in All Projects

3.1 Load Dataset

1. Imported required libraries:

   1. Pandas
   2. NumPy
   3. Matplotlib
   4. Seaborn
2. Loaded CSV / Excel file into a DataFrame

3.2 Understand the Structure

    1. `df.head()`
    2. `df.tail()`
    3. `df.shape`
    4. `df.info()`
    5. `df.describe()`
    

3.3 Check Data Types

1. Identified:

   1. Numerical columns
   2. Categorical columns
   3. Date / Time columns

---

### 3.4 Handle Missing Values

1. Checked using:

   1. `df.isnull().sum()`
2. Handled by:

   1. Dropping rows / columns
   2. Filling using mean, median, or mode

---

### 3.5 Handle Duplicates

1. Checked using:

   1. `df.duplicated().sum()`
2. Removed using:

   1. `df.drop_duplicates()`

---

### 3.6 Handle Outliers

1. Used:

   1. Boxplots
   2. IQR Method (Q1, Q3, IQR, Lower & Upper Bounds)

---

### 3.7 Univariate Analysis

1. Numerical:

   1. Histogram
   2. KDE Plot
2. Categorical:

   1. Count Plot
   2. Bar Chart

---

### 3.8 Bivariate Analysis

1. Categorical vs Numerical:

   1. Boxplot
2. Numerical vs Numerical:

   1. Scatterplot
   2. Correlation

---

### 3.9 Multivariate Analysis

1. Correlation Heatmap
2. Pairplot

---

### 3.10 Feature Engineering

1. Created new columns
2. Applied transformations:

   1. Log Transformation
   2. Standardization
   3. Encoding

---

### 3.11 Remove Irrelevant Columns

1. Dropped unnecessary columns based on:

   1. Domain knowledge
   2. Business logic

---

### 3.12 Final Clean Dataset Export

1. Saved clean dataset using:

```python
df.to_csv("clean_data.csv", index=False)
```

---

## 4. 🧾 Final EDA Workflow Summary

| Step No | Task                  |
| ------: | --------------------- |
|       1 | Load Data             |
|       2 | View Structure        |
|       3 | Check Data Types      |
|       4 | Handle Missing Values |
|       5 | Handle Duplicates     |
|       6 | Handle Outliers       |
|       7 | Univariate Analysis   |
|       8 | Bivariate Analysis    |
|       9 | Multivariate Analysis |
|      10 | Feature Engineering   |
|      11 | Drop Unwanted Columns |
|      12 | Export Clean Data     |

---

## 5. 🛠️ Tools & Technologies Used

1. Python
2. Pandas
3. NumPy
4. Matplotlib
5. Seaborn
6. Jupyter Notebook

---

## 6. 🎯 Key Skills Demonstrated

1. Data Cleaning
2. Data Visualization
3. Statistical Analysis
4. Feature Engineering
5. Business Insight Generation
6. End-to-End EDA Workflow

---

## 7. 👤 Author

 **Vishwaprasad**

Aspiring Data Analyst
Skills: Excel | Power BI | SQL | Python | Data Analysis


