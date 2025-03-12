EDA and Data Preprocessing

📌 Project Overview

This project focuses on Exploratory Data Analysis (EDA) and Data Preprocessing to enhance the quality and reliability of data before applying machine learning techniques. The dataset used in this project contains information about employees, including their company, age, salary, place, and gender.

📂 Dataset

The dataset can be accessed here: Google Drive Link.

🛠️ Installation & Setup

To run this project, follow these steps:

Clone this repository:

git clone [https://github.com/yasirpt07/EDA-and-Pre-processing]

Install required dependencies:

pip install pandas numpy seaborn matplotlib scikit-learn

Run the Jupyter Notebook or Python script:

python eda_preprocessing.py

🔍 Methodology

This project follows a structured approach covering the following key components:

1. Data Exploration

Displayed dataset structure and unique values.

Performed statistical analysis.

Renamed columns where necessary.

2. Data Cleaning

Identified missing values and handled them (replacing with mean/median/mode).

Removed duplicate rows.

Found and treated outliers.

Fixed inconsistent formatting (e.g., company names and place names).

3. Data Analysis

Filtered employees with Age > 40 and Salary < 5000.

Created visualizations:

Scatter plot of Age vs Salary.

Count plot showing the number of employees from each place.

4. Data Encoding

Converted categorical variables into numerical values using Label Encoding.

5. Feature Scaling

Applied StandardScaler and MinMaxScaler to normalize Age and Salary.

📊 Results

Cleaned and preprocessed dataset ready for machine learning.

Insights visualized through various charts.

Standardized feature values for better model performance.

💡 Future Improvements

Implement advanced outlier detection techniques.

Experiment with different encoding techniques.

Use automated pipelines for preprocessing.
