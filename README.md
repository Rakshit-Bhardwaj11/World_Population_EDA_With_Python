# World Population EDA

## Objective
Perform Exploratory Data Analysis (EDA) on population data from **234 countries**, categorized by **continent**, across multiple decades.

---

## Dataset Overview

- **Total Entries:** 234 countries  
- **Time Span:** 1970 to 2022  
- **Categorical Columns:** Continent, Country
- **Numeric Columns:**  
  - Year-wise Population (1970 to 2022)  
  - Area (km²)  
  - Density (per km²)  
  - Growth Rate  
  - World Population Percentage  

---

## Key Insights

- **Asia** consistently has the **highest population**, followed by **Africa** and **Europe**  
- **Strong positive correlation (0.99)** across all year-wise population columns  
- **Negative correlation** observed between population and **growth rate** & **density**  
- **Area vs Population:** Medium correlation (~**0.45**), indicating that more populous countries are not always geographically larger  

---

## Visualizations

- ### Line Plot (Matplotlib)
  - Shows **continent-wise population trends** from 1970–2022  
  - **Asia** shows steep dominance; **Oceania** remains the lowest  

- ### Heatmap (Seaborn)
  - Displays **correlation matrix** between all numerical columns  
  - Highlights strong **interrelationships** and **data trends**  

---

## Tools Used

- **Python**, **Pandas** – Data cleaning & manipulation  
- **Matplotlib**, **Seaborn** – Data visualization  
- **Jupyter Notebook** – Development environment  

---

## Skills Demonstrated

- Data wrangling using **pandas**  
- Grouping & aggregating by **continent**  
- Statistical analysis: **mean**, **correlation**, etc.  
- Visualization for **trend and pattern recognition**

---
