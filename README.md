📊 Sales Data Analysis Using NumPy Array Operations
📌 Project Overview

This project demonstrates how NumPy array operations can be used to perform efficient sales data analysis.
The objective is to analyze supermarket sales data using vectorized computation, statistical functions, indexing, and broadcasting provided by the NumPy library.

The project focuses on extracting meaningful insights such as:

Total sales and average sales

Profit analysis

Statistical measures (mean, median, variance, standard deviation)

Category-based filtering

Revenue calculation using broadcasting

🎯 Objectives

The project applies core NumPy concepts:

✔ Convert sales dataset into NumPy arrays
✔ Perform mathematical computations
✔ Apply statistical analysis
✔ Use indexing & slicing techniques
✔ Implement broadcasting for revenue calculation
✔ Perform vectorized operations for performance

🗂 Dataset Description

The dataset contains typical supermarket sales attributes:

Product Category

Quantity Sold

Unit Price

Total Sales

Profit / Gross Income

Example:

Category	Quantity	Unit Price	Profit
Groceries	10	50	100
Electronics	2	20000	5000
Clothing	5	1200	300
🛠 Technologies Used

Python

NumPy

(Optional) Pandas for CSV loading

⚙ Key NumPy Features Used

This project showcases:

NumPy Arrays

Broadcasting

Vectorized Computation

Indexing & Slicing

Statistical Functions

Logical Filtering

📈 Analysis Performed

Some operations performed in this project:

✅ Revenue Calculation using Broadcasting
✅ Total & Average Sales Calculation
✅ Profit Analysis
✅ Mean, Median, Variance, Standard Deviation
✅ Filtering Sales by Category

🚀 How to Run the Project
1️⃣ Install Dependencies
pip install numpy pandas
2️⃣ Run the Script
python sales_analysis.py
💡 Sample Code Snippet
import numpy as np

quantity = np.array([10, 2, 5])
unit_price = np.array([50, 20000, 1200])

sales = quantity * unit_price   # Broadcasting

print("Sales:", sales)
print("Total Sales:", np.sum(sales))
print("Average Sales:", np.mean(sales))
✅ Learning Outcomes

Through this project, we understand:

✔ Why NumPy is faster than traditional loops
✔ How vectorized operations improve performance
✔ How statistical analysis is simplified using NumPy
✔ How broadcasting reduces code complexity

📚 Future Improvements

Possible extensions:

Load large real-world datasets

Visualize results using Matplotlib

Add predictive analytics

Build dashboard using Streamlit

👨‍💻 Author
Name: Tharun Sasi
