# 🎬 Netflix Data Cleaning & Analysis

### 📊 Project Overview
This project focuses on cleaning and analyzing the **Netflix Movies and TV Shows** dataset. The goal is to uncover trends in content additions, geographical distribution, and genre popularity. By leveraging Python's data science libraries, I transformed raw, messy data into actionable insights.

---

### 📂 Dataset Source
The data used in this project is sourced from **Kaggle**:
🔗 [Netflix Movies and TV Shows Dataset](https://www.kaggle.com/datasets/shivamb/netflix-shows)

---

### 🛠️ Key Files
- **`Netflix-data-analysis.ipynb`**: The main Jupyter Notebook containing the Python code for data cleaning, EDA, and visualization.
- **`enetflix_data.csv`**: The raw dataset used for the analysis.

---

### 🔍 Key Findings & Insights
After thorough cleaning and analysis of **5,397** records, here are the concrete results:

#### 1. Content Distribution
**69.6%** of the content on Netflix consists of **Movies**, while **30.4%** are **TV Shows**.
![Content Distribution Bar Graph](Netflix-data-analysis/Bar-Graph.png)
![Overall Content Type Distribution Pie Chart](Netflix-data-analysis/Pie-Chart.png)

#### 2. Top Producing Countries
The analysis identified the major hubs for Netflix content:
1. **United States:** Leading with over **2,000+** titles.
2. **India:** The second largest contributor.
3. **United Kingdom:** Holding the third position.
![Top 10 Producing Countries Bar Graph](Netflix-data-analysis/Bar-Graph2.png)

#### 3. Content Growth & Release Trends
A significant surge in content additions was observed starting from **2016**, peaking around **2019-2020**. Most movies added were released between **2017 and 2021**.
![Netflix Content Release Trends Barh Graph](Netflix-data-analysis/Barh-Graph2.png)
![Netflix Content Release Trends Histogram](Netflix-data-analysis/Histogram.png)

#### 4. Rating Analysis
Explored the distribution of content ratings (e.g., TV-MA, TV-14) to understand the target audience.
![Content Rating Distribution Barh Graph](Netflix-data-analysis/Barh-Graph.png)

---

### 💡 Conclusion
The analysis highlights Netflix's heavy investment in original movies over TV series and its strong focus on the US and Indian markets. The data cleaning process involved handling missing values for directors and cast, and correcting inconsistent date formats to ensure accurate time-series analysis.

---

### 🛠️ Tech Stack
- **Python** (Pandas, NumPy)
- **Matplotlib & Seaborn** (Data Visualization)
- **Jupyter Notebook**
