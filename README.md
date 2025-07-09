# 👨‍💼 Adult Income Data Analysis

This project focuses on exploratory data analysis (EDA) of the Adult Income (Census) dataset using Python. The goal is to extract meaningful insights related to demographic attributes and their relationship with income levels, especially identifying factors that influence whether a person earns more than 50K annually.

---

## 📊 Key Analysis Performed

1. Displayed the top and bottom 10 rows of the dataset
2. Found the shape of the dataset (rows and columns)
3. Retrieved detailed dataset info (datatypes, memory usage)
4. Fetched a random 50% sample from the data
5. Checked for null values and performed data cleaning
6. Replaced '?' entries with NaN and dropped missing values
7. Detected and removed duplicate records
8. Generated summary statistics for numerical columns
9. Dropped unnecessary columns: education-num, capital-gain, capital-loss
10. Analyzed age distribution and filtered data for ages 17 to 48
11. Explored the distribution of the workclass column
12. Counted individuals with Bachelors and Masters degrees
13. Performed bivariate analysis between variables
14. Converted salary values into binary format (0 for <=50K, 1 for >50K)
15. Identified the workclass group with the highest proportion of high earners
16. Compared income levels across gender
17. Converted the workclass column to category datatype for optimization

---

## 🧰 Tools and Libraries Used

- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Jupyter Notebook

---

## 📂 Dataset Overview

The dataset includes personal and professional details such as:

- Age
- Workclass
- Education
- Marital Status
- Occupation
- Relationship
- Race
- Sex
- Hours per week
- Native country
- Income category

---

## 🚀 How to Run

1. Clone this repository
2. Install the required libraries:
