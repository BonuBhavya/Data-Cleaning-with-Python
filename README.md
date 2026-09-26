# Data Cleaning with Python

## 📌 Project Overview

This project demonstrates basic **data cleaning techniques using Python** with the help of **Pandas** and **NumPy**.

The project creates a sample customer dataset and performs different data cleaning operations such as removing duplicate records, handling missing values, and interpolating missing scores.

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy

## 🔍 Data Cleaning Techniques

The project includes the following steps:

1. **Removing Duplicates**
   Duplicate rows are identified and removed using `drop_duplicates()`.

2. **Missing Value Imputation**

   * Missing values in the **Age** column are replaced using the median.
   * Missing values in the **Income** column are replaced using the mean.

3. **Linear Interpolation**
   Missing values in the **Score** column are filled using linear interpolation.

4. **Removing Remaining Null Values**
   Any remaining null values are removed using `dropna()`.

## 📂 Project Structure

```text
Data-Cleaning-with-Python/
│
├── data_cleaning_python.py
└── README.md
```

## ▶️ How to Run

1. Install Python on your system.
2. Install the required libraries:

```bash
pip install pandas numpy
```

3. Run the Python file:

```bash
python data_cleaning_python.py
```

## 🎯 Objective

The main objective of this project is to demonstrate how Python libraries such as Pandas and NumPy can be used to clean and prepare data for further analysis.

## 👩‍💻 Author

BonuBhavya
