# Netflix Data Cleaning & Analysis Project:
Project OverviewThis project focuses on cleaning and exploring the Netflix Movies and TV Shows dataset. The primary goal was to transform raw, inconsistent data into a structured format suitable for analysis, followed by an exploratory data analysis (EDA) to uncover trends in Netflix's content library.
# Tools & TechnologiesLanguage:
•Python 
•Libraries: Pandas (Data Manipulation), NumPy (Numerical Analysis), Matplotlib & Seaborn (Data Visualization).
•Environment: Jupyter Notebook / Kaggle.
# Data Cleaning Process (Key Highlights):
To ensure data integrity, I performed the following steps:
• Handling Missing Values: Addressed 778 missing values in the column and handled nulls in director,country and cast
• Data Type Conversion: Standardized the date_added column to a proper datetime format.
• Feature Engineering: Extracted the "Primary Country" from the country column to enable accurate geographical analysis.
• Duplicate Removal: Verified and removed any duplicate entries to maintain a unique dataset.
# Key Insights & Visualizations:
• Content Distribution: Analyzed the ratio between Movies and TV Shows on the platform.
• Top Producing Countries: Identified the top 10 countries contributing to Netflix's library (led by the US and India).
• Rating Analysis: Explored the distribution of content ratings (e.g., TV-MA, TV-14) to understand the target audience.
• Release Trends: Visualized how Netflix has expanded its content production over the years.
# How to Use: 
1- Clone this repository.
2- Install dependencies: pip install pandas matplotlib seaborn.
3- Run the Jupyter Notebook: Netflix_Analysis.ipynb
# Original Notebook on Kaggle:
-> /kaggle/input/datasets/ahmedosman220/netflix-shows/Netflix_data.csv
