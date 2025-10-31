# MSCS 634 – Lab 1: Data Visualization, Preprocessing, and Statistical Analysis

**Author:** Safal Poudel  
**Course:** MSCS 634 – Advanced Big Data and Data Mining 
**Instructor:** Prof. Satish Penmatsa
**Lab Assignment:** Lab 1 – Data Visualization, Preprocessing, and Statistical Analysis  

---

## Purpose

The purpose of this lab was to apply foundational techniques in **data visualization, preprocessing, and statistical analysis** using Python in JupyterLab.  
The work demonstrates how to load, explore, clean, and analyze a dataset to gain meaningful insights.  
Specifically, the lab covers:

- Exploratory visualizations (scatter plots, histograms, bar charts, etc.)
- Handling missing values, outliers, and data reduction
- Scaling and discretizing continuous data
- Computing descriptive statistics and correlations to summarize dataset behavior

This end-to-end process prepares raw data for deeper modeling or predictive analysis.


## Key Insights

### From Visualizations
- **Sales and Profit Relationship:** The scatter plot showed that higher sales don’t always translate to higher profits—some high-revenue transactions even resulted in losses due to heavy discounting.  
- **Revenue Distribution:** The histogram revealed a strong **right-skew**, meaning a few very large sales dominate the dataset.  
- **Profit by Category:** The box plot indicated that *Electronics* products tend to have the widest profit variability, highlighting potential pricing inefficiencies.  
- **Regional Distribution:** The pie chart showed near-balanced sales activity across regions, with a slight concentration in the North and South.

### From Statistical Measures
- The **mean revenue** exceeded the **median**, confirming the right-skewed pattern observed visually.  
- **Variance and standard deviation** showed significant spread in revenue and profit, indicating high volatility.  
- The **correlation matrix** confirmed a strong positive correlation between revenue and profit, as expected, while discount correlated negatively with profit.


## Challenges

- **Environment Setup:** Using JupyterLite initially prevented pip installations; switching to Google Colab solved the issue.    
- **Missing Values:** Numeric columns were filled with the column mean, while categorical columns used mode replacement to preserve dataset integrity.   

This lab successfully demonstrates a complete data analysis workflow—from raw data to cleaned, visualized, and statistically summarized insights.  

