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
• Plots:
1-The Distribution in Typ column:![The Distribution](<img width="389" height="412" alt="image" src="https://github.com/user-attachments/assets/a42742ae-a5ab-4767-a0dc-1648862cda47" />
)
2-The Country produces most content on Netflix: ![The Producing Countries](<img width="584" height="460" alt="image" src="https://github.com/user-attachments/assets/03e5a1ed-8c72-4d56-976d-e1d342c4c468" />
)
3-The Top 10 Ratings in Netflix:![Top Ratings](<img width="584" height="480" alt="image" src="https://github.com/user-attachments/assets/f3d63183-48b9-4175-a0a5-c8dab6c6a311" />
)
4-The Top 10 Movies Director:![Top Movies Director](<img width="712" height="460" alt="image" src="https://github.com/user-attachments/assets/0ca894f7-e219-4ae8-a67b-a5ac9d48af23" />
)
5-Visualize The Duration of TV Show:![The Duration of TV Show](<img width="641" height="480" alt="image" src="https://github.com/user-attachments/assets/28939765-c709-4107-a25d-e5295e7dd5aa" />
)
# How to Use: 
1- Clone this repository.
2- Install dependencies: pip install pandas matplotlib seaborn.
3- Run the Jupyter Notebook: Netflix_Analysis.ipynb
# Original Notebook on Kaggle:
-> /kaggle/input/datasets/ahmedosman220/netflix-shows/Netflix_data.csv
