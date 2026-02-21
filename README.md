## Exploratory analysis of global health inequalities
### **Aim**
To explore and analyse the relationship between socioeconomic level and global health worldwide.

### **Methods**

**Data Source**: downloaded from World Bank Data as .xlsx. Years 2000 - 2024.

https://data.worldbank.org/ 

**Software & Tools**: Analysis performed with Python version 3.13.7 using the following libraries: Pandas, Numpy, Plotly, Statsmodels

**Indicators included**:

Economic Indicators
-	GDP per capita (current US$).
-	GNI per capita (Atlas method).
-	GDP growth (annual %).
-	Gini index.
-	Central_government_debt,_total_(%_of_GDP)
-	Current_health_expenditure_(%_of_GDP)

Health Indicators:
-	Life expectancy at birth, total (years).
-	Mortality rate, infant (per 1,000 live births).
-	UHC Service Coverage Index.
-	Maternal mortality ratio (modeled estimate, per 100,000 live births).
-	People using at least basic sanitation services (% of population).
-	People using at least basic drinking water services (% of population).
-	Hospital beds (per 1000 people).

Human Development & Well-being Indicators:
-	Human capital index (HCI) (scale 0-1).
-	Unemployment, total (% of total labor force) (national estimate).
-	Access to electricity (% of population).
-	Internet users (% of population).
-	Population total.

## Results

### World Maps

Interactive world maps have been generated for each indicator.

For example, GDP per capita (current US$) - global map covering the years 2000 – 2024

[View GDP per capita chart](Data_from_worldbank/Economic/GDP_per_capita_current_USD.html) 

Year 2023
<img width="975" height="565" alt="image" src="https://github.com/user-attachments/assets/3bdee306-4acf-405b-af5a-40a534ba6abd" />

### Horizontal barr graphs 
Horizontal barr graphs showing top and bottom ten countries per indicator.

For example, GDP per capita (current US$) - top and bottom ten counties covering the years 2000 – 2024

Year 2023

<img width="975" height="412" alt="image" src="https://github.com/user-attachments/assets/ab050943-78dd-406e-940e-d551afb8452d" />

### Line graphs
Lines graphs shoing overtime changes for all countries per indicator.

For example, GDP per capita (current US$)

<img width="975" height="394" alt="image" src="https://github.com/user-attachments/assets/06d886c1-22d3-4fd2-8034-9b6fd7e63caa" />

### Comparative analysis

For example, GDP per Capita vs GINI Index

Year 2023

<img width="975" height="403" alt="image" src="https://github.com/user-attachments/assets/3e980947-4295-4b07-a833-4c24ca8a095c" />

Interpretation:

GDP per capita indicates the average income per person.
GINI Index measures the income distribution within a country. The index goes from 0 (perfect equality - everyone earns the same) to 100 (perfect inequality - one person earns everything).



Coefficient pooled years:

<img width="369" height="118" alt="image" src="https://github.com/user-attachments/assets/72bc3940-e8ac-4e8a-8caf-206bc7c829b6" />



Coefficient year 2023 only:

<img width="369" height="115" alt="image" src="https://github.com/user-attachments/assets/2616a3b8-ec05-47e1-973a-3fc642cce91c" />


The Pearson correlation coefficient of -0.36/-0.38  indicates a modest inverse association between GDP per capita and income inequality. While higher-income countries tend to exhibit lower inequality, the relationship is not strong, suggesting that income distribution is influenced by additional factors.

# **Conclusion**

# **Summary**

## **All the graphs can be seen here:**

### World maps

#### Economic Indicators
-	GDP per capita (current US$):
https://mardedexo.github.io/global-health-inequalities/html_graphs/GDP_per_capita_current_USD.html

-	GNI per capita (Atlas method):
  
-	GDP growth (annual %).
-	Gini index.
-	Central_government_debt,_total_(%_of_GDP)
-	Current_health_expenditure_(%_of_GDP)


The full report can be seen here:

The code for each plot can be found here: 
