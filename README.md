# Task 1: Data Cleaning & Preprocessing – Airlines Dataset

Hi there!  
This repository contains my solution for **Task 1** of the AI/ML Internship – where I have used a real-world dataset of airline flights. The main goal was to clean and preprocess the data.


## About the Dataset

The dataset, `airlines_flights_data.csv`, contains over **300,000 flight records**, including details like:
- Airline name
- Source & destination cities
- Departure and arrival time slots
- Class (Economy/Business)
- Duration, Days Left, and Price


## What I Did in This Task

Here’s a summary of the preprocessing steps I followed:

1. **Explored the dataset** using Pandas to understand the structure, types, and any missing values.
2. **Simulated missing values** in numeric columns and handled them using:
   - Mean (for `duration`)
   - Median (for `days_left`)  (if necessary)
3. **Dropped irrelevant columns** (like the index column).
4. **Encoded categorical columns** using one-hot encoding (e.g., `airline`, `departure_time`, etc.).
5. **Standardized numeric features** (`duration`, `days_left`, `price`) using `StandardScaler` so they’re on the same scale.
6. **Visualized outliers** using boxplots.
7. **Removed outliers** using the IQR method to ensure cleaner input for ML models.


## Tools & Libraries Used

- Python (Google Colab)
- **Pandas** & **NumPy** – for data manipulation
- **Seaborn** & **Matplotlib** – for visualizations
- **Scikit-learn** – for standardization


## Files in This Repository

- `Task1_Data_Preprocessing_Airlines.ipynb`: My full Colab notebook with step-by-step code and explanations.
- `README.md`: this file.


Thanks for checking it out!
