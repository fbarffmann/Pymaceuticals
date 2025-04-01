# Pymaceuticals: Drug Efficacy Study on Squamous Cell Carcinoma

## Overview

This project analyzes the effectiveness of several drug regimens in treating squamous cell carcinoma (SCC) in mice. Using real-world-inspired clinical trial data, we explored tumor response and survival outcomes over a 45-day period. Our goal was to identify which treatments were most successful in reducing tumor volume and to determine the correlation between key variables like weight and tumor size.

This analysis was conducted as part of a data analytics bootcamp and highlights foundational skills in data wrangling, visualization, and statistical modeling using Python.

## Key Objectives

- Determine which drug regimens are most effective at reducing tumor size
- Visualize the distribution of tumor volume across treatments
- Identify potential correlations between mouse characteristics and tumor growth
- Apply regression and statistical techniques to assess drug performance

## Tools & Technologies

- **Python** (Pandas, Matplotlib, SciPy)
- **Jupyter Notebook**
- **Data Cleaning & Merging**
- **Descriptive & Inferential Statistics**
- **Linear Regression & Correlation Analysis**
- **Data Visualization**

## Project Highlights

- Cleaned and merged two datasets (mouse metadata and tumor observations) to ensure integrity and remove duplicate records
- Generated summary statistics for each drug regimen (mean, median, variance, etc.)
- Created visualizations:
  - **Bar charts** showing total timepoints by regimen
  - **Pie charts** showing gender distribution
  - **Box plots** comparing final tumor volume across top-performing drugs (Capomulin, Ramicane, etc.)
  - **Line charts** showing tumor progression over time for individual mice
  - **Scatter plots** and **linear regression** examining the relationship between weight and tumor volume
- Found that **Capomulin** and **Ramicane** outperformed other regimens in tumor reduction
- Demonstrated a strong positive correlation between **mouse weight** and **tumor volume** under the Capomulin regimen (R² ≈ 0.71)

## How to Run

1. Clone the repository:
   ```
   git clone https://github.com/fbarffmann/Pymaceuticals.git
   ```

2. Open the Jupyter Notebook:
   ```
   jupyter notebook pymaceuticals.ipynb
   ```

3. Step through the notebook to view data cleaning, analysis, visualizations, and final insights.

## Key Takeaways

- **Capomulin** consistently reduced tumor size and showed reliable performance over time.
- Strong correlation observed between **mouse weight** and **tumor volume** — heavier mice tended to develop larger tumors.
- Visual and statistical analyses effectively supported data-driven recommendations on treatment selection.

## License

This project is for educational purposes only and is based on simulated data provided as part of a bootcamp curriculum.

---

👨‍💻 Developed by Finn Brennan Arffmann  
📊 Learn more at [github.com/fbarffmann](https://github.com/fbarffmann)
