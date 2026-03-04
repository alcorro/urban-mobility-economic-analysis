## Urban Mobility and Economic Productivity in LATAM Cities

This project analyzes the relationship between **urban mobility performance** and **economic productivity** across major Latin American cities. By integrating traffic congestion data from the TomTom Traffic Index with economic indicators from OECD Cities, the analysis explores urban patterns that may inform **transportation planning and infrastructure prioritization**.

The workflow focuses on **data cleaning**, **standardization**, **dataset integration**, and **exploratory data analysis (EDA)** to generate data-driven insights on how congestion dynamics vary across economically different urban environments.

---

#### Tools Used

![Python](https://img.shields.io/badge/python-357ebd?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23357ebd.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-357ebd?style=for-the-badge)
![Matplotlib](https://img.shields.io/badge/Matplotlib-357ebd?style=for-the-badge)
![Data Cleaning](https://img.shields.io/badge/Data_cleaning-295F98?style=for-the-badge)
![Data Wrangling](https://img.shields.io/badge/Data_Wrangling-295F98?style=for-the-badge)
![Data Analysis](https://img.shields.io/badge/Data_analysis-295F98?style=for-the-badge)

---

### Key Questions

1. Which Latin American cities show the highest congestion levels in 2024?
2. How does congestion intensity vary across cities with different GDP per capita levels?
3. What preliminary patterns emerge between urban mobility indicators and economic productivity?

---

### Methodology

- **Data Inspection:** Evaluated dataset structure and data types using `.info()` to identify formatting issues and ensure data readiness.
- **Data Cleaning & Standardization:** Standardized column names, converted datetime fields, and cleaned numeric variables affected by locale-specific formatting.
- **Feature Engineering:** Extracted the analysis year from timestamp data and aggregated traffic metrics at the city–year level.
- **Data Integration:** Merged mobility indicators with city-level economic variables to create a unified analytical dataset.
- **Exploratory Data Analysis (EDA):** Examined distributions and cross-city differences in congestion and economic indicators using statistical summaries and visualizations.

---

### Key Findings

- Urban congestion levels vary substantially across Latin American cities, indicating heterogeneous mobility conditions within the region.
- The distribution of `jams_delay` shows meaningful dispersion, suggesting congestion intensity is strongly city-dependent.
- Comparative analysis indicates that higher GDP per capita does not consistently correspond to lower congestion levels, highlighting the complex and non-linear relationship between economic productivity and urban mobility.
- The integrated dataset establishes a solid foundation for deeper correlation and predictive analysis in future work.

---

### Featured Visualizations

1. **Jams Delay Distribution (Boxplot)**  
   The boxplot illustrates the distribution and variability of traffic delay times across cities in 2024. The visualization highlights dispersion in congestion levels and enables identification of potential outliers.

   ![Jams Delay Boxplot](/assets/p01_jams_delay_boxplot.png)

2. **Jams Delay Distribution (Enhanced View)**  
   An enhanced boxplot with mean markers provides additional visibility into the central tendency and spread of congestion delays, supporting exploratory assessment of urban traffic conditions.

   ![Jams Delay Distribution](/assets/p01_jams_delay_distribution.png)

3. **Traffic vs. Economic Output by City:**  
   The bar chart compares `jams_delay` and `city_gdp_capita` across cities, enabling visual assessment of the relationship between urban congestion and economic productivity. Preliminary patterns suggest that mobility efficiency may play a relevant role in urban economic performance, supporting the need for deeper multivariate analysis.

   ![Traffic vs Economy by City](/assets/p01_traffic_vs_economy.png)

---

### What I Learned

- Strengthened my ability to clean and standardize multi-source urban datasets.
- Improved proficiency in exploratory data analysis using Pandas, Matplotlib, and Seaborn.
- Gained experience aggregating city-level mobility indicators for comparative analysis.
- Enhanced my ability to translate data findings into insights relevant for urban planning contexts.
- Reinforced best practices for building reproducible and well-documented data analysis projects.

---

### Repository Structure
