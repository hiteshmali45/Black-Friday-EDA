# Black-Friday-EDA
Based on your uploaded Jupyter Notebook titled **`Black_Friday_(Hitesh) (1).ipynb`**, here is a `README.md` file specifically tailored to this project:

---

# Black Friday Sales Data Analysis

## 📌 Project Overview

This project involves **Exploratory Data Analysis (EDA)** on the **Black Friday Sales dataset** to uncover customer purchase behavior, shopping trends, and other insights. The aim is to understand the factors that influence purchase amounts and how different demographics interact with product categories.

## 📂 Dataset

* **Source**: [Black Friday Dataset – Kaggle](https://www.kaggle.com/datasets/sdolezel/black-friday)
* **Description**: This dataset contains customer transactions from a retail store during the Black Friday sales event.
* **Key Columns**:

  * User\_ID, Product\_ID
  * Gender, Age, Occupation, City\_Category
  * Stay\_In\_Current\_City\_Years, Marital\_Status
  * Product\_Category\_1/2/3
  * Purchase (Target variable)

## 📊 Key Objectives

* Clean and preprocess the dataset
* Analyze missing data and handle it properly
* Perform univariate and bivariate analysis
* Visualize trends using appropriate plots
* Understand relationships between demographics and purchase behavior
* Identify which customer groups contribute the most to sales

## 🔧 Tools & Libraries Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn

## 🧹 Data Cleaning Steps

* Removed irrelevant or duplicate data
* Handled missing values in `Product_Category_2` and `Product_Category_3`
* Converted categorical columns to proper data types
* Created new features for better segmentation and visualization

## 📈 Visualizations & Insights

The analysis answers key business questions such as:

* Which age group spends the most?
* Are men or women more likely to shop during Black Friday?
* Which city category has the highest average purchase?
* How does marital status affect purchase behavior?
* What product categories are most frequently purchased?

### Sample Findings:

* Males tend to spend more on average than females.
* People aged 26–35 are the largest spenders.
* City Category B has the highest total sales.
* Product Category 1 dominates in terms of total purchases.

## 📁 File Structure

```
Black_Friday_(Hitesh).ipynb   # Jupyter Notebook with complete EDA
README.md                     # Project documentation
```

## ✅ How to Run

1. Clone this repository https://github.com/hiteshmali45/Black-Friday-EDA
2. Make sure you have Python 3.x installed with the following libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn
   ```
3. Open and run the notebook:

   ```bash
   jupyter notebook Black_Friday_(Hitesh).ipynb
   ```
