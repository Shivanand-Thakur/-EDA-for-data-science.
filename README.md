# -EDA-for-data-science.
This Jupyter notebook performs data cleaning and exploratory analysis on a Cardiotocographic dataset. It uses Pandas and NumPy for preprocessing, imputes missing values, and employs Matplotlib/Seaborn for visualization to prepare the data for further analysis or modeling.

# Cardiotocographic Data Cleaning and Analysis

## 📌 Overview
This Jupyter notebook focuses on cleaning and exploring a **Cardiotocographic (CTG)** dataset. The goal is to preprocess the data by handling missing values and visualizing distributions, ensuring the dataset is ready for further machine learning or statistical analysis.

## 🧠 Key Tasks
- Load and inspect the dataset  
- Identify and handle missing values:
  - **Numeric columns:** Filled with median values  
  - **Categorical columns:** Filled with mode values  
- Explore dataset structure using `info()` and `head()`  
- Visualize data distributions using Matplotlib and Seaborn

## 🛠️ Technologies Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook

## 📂 Dataset
The notebook uses `Cardiotocographic.csv`, which should be placed in the correct path (e.g., `./dataset/` or Google Drive as referenced).

## 🚀 How to Run
1. Install required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn
