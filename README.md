# ELEVATE LABS TASK1- Data Cleaning and Preprocessing
Mall Customer Segmentation – Data Preprocessing & EDA
Overview
This project begins the journey of customer segmentation by preparing and exploring the Mall Customers dataset. The dataset includes demographic and behavioral features that will later be used for clustering. The current stage focuses on data cleaning, feature understanding, and exploratory analysis.

Objective
Clean and prepare the Mall Customers dataset

Understand key features that influence customer behavior

Set the foundation for applying machine learning models for segmentation

Tools & Technologies Used
Python

Jupyter Notebook / Google Colab

Libraries:

pandas – for data loading and manipulation

numpy – for numerical operations

matplotlib, seaborn – for data visualization

Dataset Details
Name: Mall_Customers.csv

Features:

CustomerID: Unique customer identifier

Gender: Male/Female

Age: Age of the customer

Annual Income (k$): Yearly income in thousands

Spending Score (1–100): Based on customer behavior and purchasing data

Steps Completed
Data Loading

Imported dataset using pandas.read_csv()

Checked dataset shape and top records using .head()

Missing Value Handling

Verified there were no null or missing values using .isnull().sum()

Data Types & Basic Info

Used .info() to inspect data types

Confirmed numeric types for Age, Income, and Spending Score

Descriptive Statistics

Used .describe() to analyze distributions (mean, min, max, std)

Exploratory Data Analysis (EDA)

Gender distribution via countplot

Age distribution using histogram

Annual Income and Spending Score visualized with histograms and KDE plots

Identified value ranges and outliers, set stage for scaling/clustering

Insights from EDA
Balanced gender distribution (slightly more females)

Customers span a wide age range with most between 30–40

Spending behavior and income are not always directly correlated

Dataset is clean and ready for feature scaling and clustering

Next Steps (Planned)
Feature selection for clustering

Use K-Means to segment customers

Visualize clusters for marketing insights

Created by
Shaik Rubeena 
Date: April 2025
