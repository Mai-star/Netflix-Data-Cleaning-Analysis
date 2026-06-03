# Netflix Data Cleaning & Analysis Project



## Project Overview

This project focuses on cleaning and exploring the Netflix Movies and TV Shows dataset. The primary goal was to transform raw, inconsistent data into a structured format suitable for analysis, followed by an exploratory data analysis (EDA) to uncover trends in Netflix's content library.



## Tools & Technologies

- **Language:** Python
- 
- **Libraries:** Pandas (Data Manipulation), NumPy (Numerical Analysis), Matplotlib & Seaborn (Data Visualization).
- 
- **Environment:** Jupyter Notebook / Kaggle.
- 


## Data Cleaning Process (Key Highlights)

To ensure data integrity, I performed the following steps:

- **Handling Missing Values:** Addressed 778 missing values in the column and handled nulls in director, country and cast.
- 
- **Data Type Conversion:** Standardized the `date_added` column to a proper datetime format.
- 
- **Feature Engineering:** Extracted the "Primary Country" from the `country` column to enable accurate geographical analysis.
- 
- **Duplicate Removal:** Verified and removed any duplicate entries to maintain a unique dataset.
- 


## Key Insights & Visualizations



### Content Distribution

Analyzed the ratio between Movies and TV Shows on the platform.

![Content Distribution Bar Graph](Netflix-data-analysis/Bar-Graph.png)



### Top Producing Countries

Identified the top 10 countries contributing to Netflix's library (led by the US and India).

![Top 10 Producing Countries Bar Graph](Netflix-data-analysis/Bar-Graph2.png)



### Rating Analysis

Explored the distribution of content ratings (e.g., TV-MA, TV-14) to understand the target audience.

![Content Rating Distribution Barh Graph](Netflix-data-analysis/Barh-Graph.png)



### Release Trends

Visualized how Netflix has expanded its content production over the years.

![Netflix Content Release Trends Barh Graph](Netflix-data-analysis/Barh-Graph2.png)

![Netflix Content Release Trends Histogram](Netflix-data-analysis/Histogram.png)



### Overall Content Type Distribution

A pie chart showing the overall distribution of movies vs TV shows.

![Overall Content Type Distribution Pie Chart](Netflix-data-analysis/Pie-Chart.png)



## How to Run This Project Locally



To run this project on your local machine, follow these steps:



1.  **Clone the repository:**
2.  
    ```bash
    
    git clone https://github.com/Mai-star/Netflix-Data-Cleaning-Analysis.git
    
    cd Netflix-Data-Cleaning-Analysis
    
    ```
    
2.  **Create a virtual environment (recommended):**
3.  
    ```bash
    
    python -m venv venv
    
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    
    ```
    
3.  **Install the required libraries:**
4.  
    ```bash
    
    pip install -r requirements.txt
    
    ```
    
4.  **Launch Jupyter Notebook:**
5.  
    ```bash
    
    jupyter notebook
    
    ```
    
    This will open a browser window with the Jupyter interface. Navigate to `Netflix-data-analysis/Netflix-data-analysis.ipynb` and open it.
    


## Conclusion

This project successfully demonstrated a comprehensive data cleaning and exploratory data analysis workflow. The analysis revealed key insights into Netflix's content library, including content distribution, top contributing countries, rating trends, and historical growth patterns. These insights can be valuable for content strategy and understanding audience preferences.



## 

























