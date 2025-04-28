
# 📄 README.md

## Project Title:  
**Exploratory Data Analysis (EDA) on Amazon Dataset**

---

## 📚 Project Overview
This project involves performing **Exploratory Data Analysis (EDA)** on an Amazon product dataset.  
The analysis aims to understand product discounts, pricing trends, category distributions, and relationships between variables to generate actionable insights.

---

## 🗂️ Dataset Description
- **Source:** Amazon (Provided dataset)
- **Format:** CSV
- **Columns:** Includes fields such as `category`, `price`, `discount_percentage`, and others.

---

## 🔥 Steps Performed

### 1. Data Loading and Inspection
- Loaded the dataset using **Pandas**.
- Used `.info()`, `.describe()`, `.value_counts()` to understand data types, missing values, and unique value distributions.

### 2. Data Cleaning (if required)
- Checked for missing values and anomalies.
- Ensured data types were appropriate for analysis.

### 3. Visualization
- **Pairplot:** Used `sns.pairplot()` to visualize relationships between numerical features.
- **Heatmap:** Created a correlation heatmap with `sns.heatmap()` to find correlated variables.
- **Histograms:** Plotted distributions of `discount_percentage`, `price`, and other numerical features.
- **Boxplots:** Visualized the spread of discount percentages across different categories.
- **Scatterplots:** Analyzed relationships like `price vs discount_percentage` using `sns.scatterplot()`.

### 4. Observations
- Noted key patterns from each visualization.
- Highlighted outliers, skewness, and correlation findings.

### 5. Summary of Findings
- Summarized overall insights based on the visualizations and statistical exploration.

---

## 🛠️ Libraries and Tools Used
- **Pandas** for data manipulation
- **Seaborn** and **Matplotlib** for data visualization
- **Jupyter Notebook** for interactive analysis

---

## 📊 Key Findings
- Categories differ significantly in average discount percentages.
- Some products offer very high discounts, creating outliers in the dataset.
- A negative correlation observed between `price` and `discount_percentage` — higher-priced products often have lower discounts.
- Certain categories consistently offer higher discounts.
- Skewness in discount distribution observed.

---

## 📈 Visual Samples
- Pairplots showing relationships between numerical features.
- Heatmaps identifying correlated fields.
- Clean boxplots and histograms to present distributions neatly.
- Scatterplots highlighting trends across categories.

---

