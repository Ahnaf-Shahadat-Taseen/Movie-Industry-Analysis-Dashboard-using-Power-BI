# Movie Industry Analysis Dashboard using Power BI

### By: Ahnaf Shahadat Taseen | https://www.linkedin.com/in/ahnaf-shahadat-taseen-1b738a242/ | 

`#data-analysis` `#power-bi` `#business-intelligence` `#data-visualization` `#portfolio-project`

---

## 📊 Dashboard Live Demo



![https://github.com/Ahnaf-Shahadat-Taseen/Movie-Industry-Analysis-Dashboard-using-Power-BI/blob/main/Capture.PNG(image_bc0397.png)]

---

## 📝 Project Overview

This project presents a comprehensive analysis of a synthetic movie dataset containing 1 million records. The goal was to explore trends, identify key drivers of financial success, and understand audience preferences within the film industry. The interactive dashboard, built entirely in Power BI, serves as a dynamic tool for stakeholders to explore movie performance metrics from 1950 to 2025.

---

## ❓ Problem Statement & Key Questions

The primary objective was to answer critical business questions about movie performance:
1.  What are the primary drivers of a movie's profit and Return on Investment (ROI)?
2.  How do key metrics like budget, revenue, and audience ratings vary across different genres?
3.  What are the long-term trends in the movie industry regarding production and revenue?
4.  Which genres are the most produced versus the most profitable?

---

## 🛠️ Tools & Techniques

* **Data Source:** Synthetic Movie Dataset (CSV file with 999,999 rows).
* **Data Transformation:** **Power Query** was used for initial data cleaning, type checking, and creating calculated columns (e.g., Profit, ROI, Decade).
* **Data Modeling & Analysis:** **DAX (Data Analysis Expressions)** were written to create robust measures for KPIs like `Total Revenue`, `Average ROI`, and `Average IMDB Rating`.
* **Data Visualization:** **Power BI Desktop** was the primary tool for creating all charts, slicers, and interactive elements.

---

## ✨ Key Insights & Findings from the Dashboard

The dashboard reveals several key insights into the movie industry:

* **Drama is King:** The 'Drama' genre dominates across multiple metrics. It commands the **highest production budgets (2.4T)** and generates the **most profit (5T)**. This suggests that while expensive to produce, dramatic films have historically yielded the highest returns.

* **ROI is Not Just About Big Budgets:** While Drama leads in raw profit, the 'Comedy' and 'Action' genres also show a very strong **Return on Investment (ROI)**, as seen in the pie chart. This indicates that these genres are highly efficient at converting their budgets into profit.

* **High Production Volume in Drama & Comedy:** The 'IMDB Rating by Genre' bar chart (which reflects the count of movies) shows that 'Drama' and 'Comedy' are the most frequently produced genres, with **1.6M and 1.3M movies** respectively. This high volume contributes to their overall market dominance.

* **Audience Preference:** The average IMDB rating across all movies is a solid **6.49**, suggesting a generally positive reception. By filtering genres, users can explore how this rating changes for different movie types.

---

## ⚙️ Dashboard Features & Interactivity

The dashboard is fully interactive to allow for deep-dive analysis:

* **Dynamic Slicers:** Users can filter the entire report by **Country**, **Genre**, and **Year** to isolate specific data points.
* **Cross-Filtering:** Clicking on a data point in any chart (e.g., the 'Drama' bar in the budget chart) will filter all other visuals on the page to reflect that selection.
* **KPI Cards:** At-a-glance metrics at the top provide a high-level summary of the entire dataset or the filtered selection.
