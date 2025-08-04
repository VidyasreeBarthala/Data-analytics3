🧹 Data Cleaning Project – Airbnb NYC Dataset

This project is part of the Oasis Infobyte Internship (Level 1 – Project 3).
The objective is to clean and preprocess the "AB_NYC_2019" dataset using Python

📌 Objective

To clean the raw Airbnb NYC dataset by:

Handling missing values
Removing duplicates
Standardizing column names
Identifying and removing outliers in price
📁 Dataset Information

Dataset Name: AB_NYC_2019.csv
Source: Kaggle - Airbnb NYC 2019 Dataset
Size:~49,000 rows, 16 columns
Content: Airbnb listing data like host info, room type, price, availability, etc.
🧪 Tools & Libraries Used

Python
Pandas
NumPy
Matplotlib
Seaborn
🔧 Cleaning Process

Missing Values

Filled reviews_per_month with 0
Dropped rows with missing host_name and last_review
Duplicates

Removed exact duplicate rows
Column Standardization

Converted all column names to lowercase and replaced spaces with underscores
Outlier Handling

Used IQR method to remove extreme outliers from price column
Visualized with boxplot before & after
✅ Files Included

cleaned_ab_nyc_2019.csv (final cleaned version)
oasis_level 1-project 3
README.md
📈 Result
Final dataset is clean, consistent, and ready for further analysis or modeling.
All key cleaning steps have been successfully completed.

💼 Internship Info

Name: Gobika Srimaan
Internship:Oasis Infobyte – July 2025
Project: Level 1 – Data Cleaning
