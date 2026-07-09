# Immigration and Crime in Europe (2015–2024)

## Project Overview

This project presents an exploratory data analysis (EDA) of immigration trends and crime indicators across 28 European countries between 2015 and 2024.

Using public datasets and a combination of SQL, Python and Tableau, the analysis investigates immigration trends alongside three crime indicators (homicide, theft and rape) to explore whether consistent patterns exist between immigration and crime indicators.

Rather than attempting to establish causality, the project focuses on identifying patterns, comparing countries and communicating findings through clear visualizations and evidence-based interpretations.

## 📷 Dashboard Preview

The interactive Tableau dashboards summarize the main findings of the analysis and allow users to explore immigration and crime trends across Europe.

<p align="center">
  <img src="images/dashboard1.png" width="900">
</p>

## 🛠️ Technologies

| Tool | Purpose |
|------|---------|
| Python | Data cleaning, analysis and visualization |
| Pandas | Data manipulation and aggregation |
| SQL | Data preparation and transformation |
| Matplotlib | Static visualizations |
| Tableau Public | Interactive dashboards |
| Jupyter Notebook | Project development |
| Git & GitHub | Version control and portfolio publication |

## 📊 Research Questions

1. How has immigration evolved in Europe between 2015 and 2024?
2. Which countries received the highest number of immigrants in 2024?
3. Which countries experienced the highest immigration growth between 2015 and 2024?
4. Which countries experienced the largest absolute increase in immigration between 2015 and 2024?
5. How did the COVID-19 pandemic affect immigration in Europe?
6. Is there a relationship between immigration and homicide rates?
7. Is there a relationship between immigration and theft rates?
8. Is there a relationship between immigration and rape rates?
9. How do the countries with the highest immigration compare with those reporting the highest crime rates?

## 📁 Dataset

Data sources include Eurostat and official European crime statistics collected from publicly available European databases.

**Variables included**

- Country
- Year
- Number of immigrants
- Homicide rate
- Theft rate
- Rape rate

The final dataset contains:

- **28 European countries**
- **10 years of observations (2015–2024)**
- **280 observations**

Data cleaning included:

- Handling missing values
- Standardizing decimal formats
- Harmonizing country names
- Preparing SQL tables and analytical views

## ⚙️ Methodology

The project followed a complete Exploratory Data Analysis (EDA) workflow:

1. **Data Collection**
   - Collected and imported official European datasets covering immigration and crime indicators (2015–2024).

2. **Data Cleaning**
   - Removed missing values.
   - Standardized decimal separators.
   - Harmonized country names.
   - Verified data consistency across all years.

3. **Data Preparation**
   - Used SQL to transform and organize the datasets.
   - Created analytical tables and views.
   - Combined immigration and crime indicators into a single analysis dataset.

4. **Exploratory Data Analysis**
   - Calculated growth rates and absolute changes.
   - Ranked countries by immigration.
   - Compared trends before and after COVID-19.
   - Explored relationships between immigration and crime indicators.

5. **Data Visualization**
   - Created exploratory visualizations using Matplotlib.
   - Designed interactive dashboards in Tableau Public.

## 📈 Key Findings

- Immigration remained relatively stable until 2019, declined during the COVID-19 pandemic, and increased sharply from 2021 onward.
- Spain, Germany and France received the highest numbers of immigrants in 2024.
- Immigration growth varied considerably across countries, with some countries experiencing substantially larger increases than others.
- Scatter plots showed no clear relationship between immigration levels and homicide, theft or rape rates.
- Countries with the highest immigration were not the same countries reporting the highest crime rates.
- The analysis suggests that immigration alone does not explain differences in crime indicators across European countries.
- Immigration trends varied considerably across countries, highlighting the importance of country-level analysis rather than general assumptions.

## Results

The analysis found no clear evidence of a consistent relationship between immigration and homicide, theft or rape rates across the selected European countries.

Instead, immigration trends and crime indicators appeared to evolve independently in most cases, suggesting that additional socioeconomic factors should be considered when interpreting crime patterns.

## 📊 Additional Dashboard

A second dashboard provides additional visualizations of homicide and rape trends, complementing the exploratory analysis presented in the main dashboard.

<p align="center">
  <img src="images/dashboard2.png" width="900">
</p>

## 📊 Tableau Dashboard

Explore the interactive dashboard here:

👉 [Tableau Public Dashboard](https://public.tableau.com/app/profile/juan.mart.n.curci.sassone/viz/Inmigrationandcrimerelationship2015-2024/Dashboard1)

## 📂 Repository Structure

```
Europe-Crime-Analysis/
│
├── data/
├── docs/
├── images/
├── notebooks/
│   ├── 01_Exploratory_Data_Analysis.ipynb
│   └── 02_Portfolio_Final.ipynb
├── sql/
├── tableau/
├── README.md
└── requirements.txt
```
## 👤 Author

**Juan Martín Curci Sassone**

Data Analyst | Journalist | Digital Marketing Specialist

- Python
- SQL
- Tableau
- Data Visualization
- Exploratory Data Analysis

LinkedIn: [Juan Martín Curci Sassone](https://www.linkedin.com/in/jmcurci/)

GitHub: [@jmcurci](https://github.com/jmcurci)

Portfolio project developed as part of the Google Data Analytics learning path.