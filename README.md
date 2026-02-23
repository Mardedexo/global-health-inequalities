## Exploratory analysis of global health inequalities
### **Aim**
To explore and analyse the relationship between socioeconomic level and global health worldwide from 2000 to 2024.

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

#### Economic Indicators:

-	GDP per capita (current US$):
  
https://mardedexo.github.io/global-health-inequalities/world_map/GDP_per_capita_current_USD_worldMap.html  

-	GNI per capita (Atlas method):
  
https://mardedexo.github.io/global-health-inequalities//world_map/Current_health_expenditure_(%_of_GDP)_worldMap.html
  
-	GDP growth (annual %):
  
https://mardedexo.github.io/global-health-inequalities/world_map/GDP_growth_map_worldMap.html

-	Gini index:

https://mardedexo.github.io/global-health-inequalities/world_map/Gini_index_map_worldMap.html

-	Central_government_debt,_total_(%_of_GDP):
  
https://mardedexo.github.io/global-health-inequalities/world_map/Central_government_debt,_total_(%_of_GDP)_worldMap.html

-	Current_health_expenditure_(%_of_GDP):
  
https://mardedexo.github.io/global-health-inequalities/world_map/Current_health_expenditure_(%_of_GDP)_worldMap.html 


#### Health Indicators:

-	Life expectancy at birth, total (years):
  
https://mardedexo.github.io/global-health-inequalities/world_map/Life_expectancy_at_birth_2000_2023_worldMap.html

-	Mortality rate, infant (per 1,000 live births):
  
https://mardedexo.github.io/global-health-inequalities/world_map/Infant_mortality_rate_2000_2023_worldMap.html

-	UHC Service Coverage Index:
  
https://mardedexo.github.io/global-health-inequalities/world_map/UHC_Service_Coverage_Index_worldMap.html

-	Maternal mortality ratio (modeled estimate, per 100,000 live births):
  
https://mardedexo.github.io/global-health-inequalities/world_map/Maternal_mortality_ratio_(modeled_estimate,_per_100,000_live_births_worldMap.html

-	Hospital beds (per 1000 people):
  
https://mardedexo.github.io/global-health-inequalities/world_map/Hospital_beds_%28per_1%2C000%20people%29_worldMap.html


#### Human Development & Well-being Indicators:

-	Human capital index (HCI) (scale 0-1):

https://mardedexo.github.io/global-health-inequalities/world_map/Human_capital_index_(HCI)_worldMap.html

-	Unemployment, total (% of total labor force) (national estimate):
  
https://mardedexo.github.io/global-health-inequalities/world_map/Unemployment,_total_(%_of_total_labor_force)_(national_estimate)_worldMap.html

-	Access to electricity (% of population):
  
https://mardedexo.github.io/global-health-inequalities/world_map/access_to_electricity_worldMap.html

-	Internet users (% of population):
  
https://mardedexo.github.io/global-health-inequalities/world_map/Internet_users_(%_of_population)_worldMap.html

-	People using at least basic sanitation services (% of population):
  
https://mardedexo.github.io/global-health-inequalities/world_map/People%20using%20at%20least%20basic%20sanitation%20services%20(%25%20of%20population)_worldMap.html 

-	People using at least basic drinking water services (% of population):
  
https://mardedexo.github.io/global-health-inequalities/world_map/People%20using%20at%20least%20basic%20drinking%20water%20services,%20urban%20(%25%20of%20urban%20population)_worldMap.html

- Population total:
  
https://mardedexo.github.io/global-health-inequalities/world_map/Population_total_worldMap.html

### Bar graphs

#### Economic Indicators:

-	GDP per capita (current US$):
  
https://mardedexo.github.io/global-health-inequalities/bar_charts/GDP_per_capita_TopBottom10_Animated.html

-	GNI per capita (Atlas method):
  
https://mardedexo.github.io/global-health-inequalities/bar_charts/GNI_per_capita_Atlas_method_TopBottom10_Animated.html

-	GDP growth (annual %) - top 10:
  
https://mardedexo.github.io/global-health-inequalities/bar_charts/GDP_growth_Top10.html

-	GDP growth (annual %) – bottom 10:

https://mardedexo.github.io/global-health-inequalities/bar_charts/GDP_growth_Bottom10.html

-	Gini index:
  
https://mardedexo.github.io/global-health-inequalities/bar_charts/Gini_index_2000_2024.html

-	Central_government_debt,_total_(%_of_GDP):
  
https://mardedexo.github.io/global-health-inequalities/bar_charts/Central_government_debt_percent_GDP_TopBottom10_Animated.html

-	Current_health_expenditure_(%_of_GDP):
  
https://mardedexo.github.io/global-health-inequalities/bar_charts/Current_health_expenditure_(%_of_GDP).html

### Health Indicators:

-	Life expectancy at birth, total (years):
  
https://mardedexo.github.io/global-health-inequalities/bar_charts/LifeExpectancy_TopBottom10_Animated_1Decimal.html

-	Mortality rate, infant (per 1,000 live births):
  
https://mardedexo.github.io/global-health-inequalities/bar_charts/Mortality_rate,_infant_(per 1,000 live births).html

-	UHC Service Coverage Index:
  
https://mardedexo.github.io/global-health-inequalities/bar_charts/UHC_service_coverage_index).html

-	Maternal mortality ratio (modeled estimate, per 100,000 live births):
  
https://mardedexo.github.io/global-health-inequalities/bar_charts/Maternal_mortality_ratio_(modeled_estimate,_per_100,000_live_births)).html

-	People using at least basic sanitation services (% of population):
  
https://mardedexo.github.io/global-health-inequalities/bar_charts/People_using_at_least_basic_sanitation_services_(%_of_population).html

-	People using at least basic drinking water services (% of population):
  
https://mardedexo.github.io/global-health-inequalities/bar_charts/People_using_at_least_basic_drinking_water_services,_urban_(%_of_urban_population)).html

-	Hospital beds (per 1000 people):
  
https://mardedexo.github.io/global-health-inequalities/bar_charts/Hospital_beds_per_1000_people_TopBottom10_Animated.html

### Human Development & Well-being Indicators:

-	Human capital index (HCI) (scale 0-1):
  
https://mardedexo.github.io/global-health-inequalities/bar_charts/Human_Capital_Index_HCI_TopBottom10_Animated.html

-	Unemployment, total (% of total labor force) (national estimate):
  
https://mardedexo.github.io/global-health-inequalities/bar_charts/Unemployment,_total_(%_of_total_labor_force)_(national_estimate)).html

-	Access to electricity (% of population):
  
https://mardedexo.github.io/global-health-inequalities/bar_charts/Access_to_electricity_(%_of_population).html

-	Internet users (% of population):
  
https://mardedexo.github.io/global-health-inequalities/bar_charts/Individuals_using_the_Internet_(%_of_population).html

-	Population total – top 10:

-	https://mardedexo.github.io/global-health-inequalities/bar_charts/Population_total_Top10.html
  
-	Population total – bottom 10:
  
https://mardedexo.github.io/global-health-inequalities/bar_charts/Population_total_Bottom10.html


### Line graphs

#### Economic Indicators:

-	GDP per capita (current US$):
  
https://mardedexo.github.io/global-health-inequalities/line_graphs/GDP_per_capita_(current_US$).html

-	GNI per capita (Atlas method):
  
https://mardedexo.github.io/global-health-inequalities/line_graphs/GNI_per_capita,_Atlas_method_(current_US$).html

-	GDP growth (annual %):
  
https://mardedexo.github.io/global-health-inequalities/line_graphs/GDP_growth_(annual_%).html

-	Gini index:
  
https://mardedexo.github.io/global-health-inequalities/line_graphs/Gini_index.html

-	Central_government_debt,_total_(%_of_GDP):
  
https://mardedexo.github.io/global-health-inequalities/line_graphs/Central_government_debtTotal.html

-	Current_health_expenditure_(%_of_GDP):
  
https://mardedexo.github.io/global-health-inequalities/line_graphs/Current_health_expenditure_(%_of_GDP).html

#### Health Indicators:

-	Life expectancy at birth, total (years):
  
https://mardedexo.github.io/global-health-inequalities/line_graphs/Life_Expectancy_by_Country_Dropdown.html

-	Mortality rate, infant (per 1,000 live births):
  
https://mardedexo.github.io/global-health-inequalities/line_graphs/Mortality_rate,_infant_(per_1,000_live_births).html

-	UHC Service Coverage Index:
  
https://mardedexo.github.io/global-health-inequalities/line_graphs/UHC_service_coverag_index.html

-	Maternal mortality ratio (modeled estimate, per 100,000 live births):
  
https://mardedexo.github.io/global-health-inequalities/line_graphs/Maternal_mortality_ratio_(modeled_estimate,_per_100,000_live_births).html

-	People using at least basic sanitation services (% of population):
  
https://mardedexo.github.io/global-health-inequalities/line_graphs/People_using_at_least_basic_sanitation_services_(%_of_population).html

-	People using at least basic drinking water services (% of population):
  
https://mardedexo.github.io/global-health-inequalities/line_graphs/People_using_at_least_basic_drinking_water_services,_urban_(%_of_urban_population).html

-	Hospital beds (per 1000 people):
  
https://mardedexo.github.io/global-health-inequalities/line_graphs/Hospital_beds_(per_1,000_people).html

#### Human Development & Well-being Indicators:

-	Human capital index (HCI) (scale 0-1):
  
https://mardedexo.github.io/global-health-inequalities/line_graphs/Human_capital_index_(HCI)_(scale_0-1).html

-	Unemployment, total (% of total labor force) (national estimate):
  
https://mardedexo.github.io/global-health-inequalities/line_graphs/Unemployment,_total_(%_of_total_labor_force)_(national_estimate).html

-	Access to electricity (% of population):
  
https://mardedexo.github.io/global-health-inequalities/line_graphs/Access_to_electricity.html

-	Internet users (% of population):
  
https://mardedexo.github.io/global-health-inequalities/line_graphs/Individuals_using_the_Internet.html

-	Population total:
  
https://mardedexo.github.io/global-health-inequalities/line_graphs/Population,_total.html

### Comparative analysis

- GDP per Capita vs GINI Index:
  
https://mardedexo.github.io/global-health-inequalities

- GDP per capita vs HCI (2020):
  
https://mardedexo.github.io/global-health-inequalities/comparative_analysis/GDP_vs_HCI.html

- GDP_vs_HCI_PopSize (2020):

https://mardedexo.github.io/global-health-inequalities/comparative_analysis/GDP_vs_HCI_PopSize.html

- UHC vs Life Expectancy (2000-2023):
  
https://mardedexo.github.io/global-health-inequalities/comparative_analysis/UHC_vs_LifeExpectancy_Animated_2000_2023.html

- GDP per capita vs Gini Index:

https://mardedexo.github.io/global-health-inequalities/comparative_analysis/GDP_per_Capita_vs_Gini_Animated_2000_2024.html

 - GINI index vs infants mortality:
   
https://mardedexo.github.io/global-health-inequalities/comparative_analysis/Gini_vs_InfantMortality_Animated_2000_2024.html

- GDP_vs_GINI Index vs GDP growth vs Population:

https://mardedexo.github.io/global-health-inequalities/comparative_analysis/GDP_vs_Gini_vs_GDP_growth_Animated_2000_2024.html


The full report can be seen here: https://mardedexo.github.io/global-health-inequalities/Full_Report.pdf 

The code for each plot can be found here: 
