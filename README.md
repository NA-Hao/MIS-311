
## Dataset Information

**Dataset:** Life Expectancy Dataset

**Dataset Summary**

- Rows: **180** (after data cleaning)
- Columns: **6**

### Variables

- Country
- Region
- Infant_deaths
- Under_five_deaths
- Adult_mortality
- Life_expectancy

---

## Data Cleaning

Before analysis, the dataset was cleaned to improve data quality.

- Missing values in Under_five_deaths and Adult_mortality were replaced using the mean of each column.
- Three duplicate rows were identified and removed.
- The cleaned dataset was then used for descriptive statistical analysis.

---
## Descriptive Statistics

<img width="924" height="290" alt="image" src="https://github.com/user-attachments/assets/749c7455-15ee-4dab-9281-fa3cb74918f4" />


## Insight

The descriptive statistics indicate that adult mortality varies considerably across countries**, with the highest standard deviation (111.49) among all variables. In comparison, life expectancy has a mean of 68.86 years and a much lower standard deviation (9.20), suggesting that while mortality levels differ greatly between countries, life expectancy is relatively more consistent.

# Figure 1 – Distribution of Life Expectancy

<img width="758" height="455" alt="image" src="https://github.com/user-attachments/assets/c8e4e047-93aa-4769-8029-348e215cc2cf" />


### Insight

The histogram indicates that most countries have a life expectancy between approximately 65 and 80 years. Only a small number of countries have considerably lower life expectancy, suggesting that extremely poor health outcomes are relatively uncommon in this dataset.

---

# Figure 2 – Adult Mortality vs Life Expectancy

<img width="752" height="456" alt="image" src="https://github.com/user-attachments/assets/49a65211-1daf-4c5d-8720-4a415742dfba" />


### Insight

The scatter plot reveals a negative relationship between adult mortality and life expectancy. Countries with higher adult mortality generally have lower life expectancy. This suggests that improving healthcare services and reducing adult mortality could significantly increase the average lifespan of a population.

---

# Figure 3 – Average Life Expectancy by Region

<img width="1350" height="445" alt="image" src="https://github.com/user-attachments/assets/c63d9e14-399c-4fca-816b-1abf8049d321" />


### Insight

The column chart shows clear differences in average life expectancy among regions. Regions with higher healthcare quality, better living standards, and stronger public health systems generally achieve higher life expectancy than other regions.

---

## Conclusion

This project demonstrates how Exploratory Data Analysis (EDA) can transform raw data into meaningful business insights. Through data cleaning, descriptive statistics, and visualization, the analysis highlights the importance of reducing adult mortality and improving healthcare systems to increase life expectancy across different regions.

---

## Tools Used

- Microsoft Excel
- Data Cleaning
- Descriptive Statistics
- PivotTable
- Histogram
- Scatter Plot
- Column Chart

---

