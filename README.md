# Socio-Economic Factors Influencing Country's Happiness: Overview of 2023

This project was completed collaboratively with my teammates as part of a group assignment (Uma Selvaraj, Sindhuja Sirigeri and Zejing Liang)

For my portfolio, I have edited and refined the project, focusing on data cleaning and presentation, while retaining the core analysis and findings. All original data sources, including the CSV files, remain linked for transparency and reproducibility. 

This project aims to investigate the factors influencing national happiness and trends over time. Key research questions include whether a country's happiness score correlates with its GDP per capita and if predicted life expectancy impacts happiness. Additionally, we will determine the happiest continent based on global happiness score. Furthermore, we will analyse happiness trends from 2018 to 2024 for specific countries like Australia, Spain, China, and the USA. By collecting and analysing relevant data on economic indicators, happiness metrics, and life expectancy, this study will provide insights into the socio-economic drivers of happiness and how they evolve over time across different regions.



## Data Sources:

2018,2019,2020 csv:https://www.kaggle.com/datasets/unsdsn/world-happiness
2021csv:https://www.kaggle.com/datasets/ajaypalsinghlo/world-happiness-report-2021
2022csv:https://www.kaggle.com/datasets/ajaypalsinghlo/world-happiness-report-2022
2023csv:https://www.kaggle.com/datasets/ajaypalsinghlo/world-happiness-report-2023
2024csv:https://www.kaggle.com/datasets/ajaypalsinghlo/world-happiness-report-2024


## Project Structure:

- **Data Combining and Cleaning**: The process of merging multiple datasets, cleaning, and preparing them for analysis is located in the notebook [`data_cleaning_combining.ipynb`](link_to_notebook).
- **Main Analysis**: All further analysis, including statistical tests, visualizations, and conclusions, can be found in the notebook [`main_ipynb`](link_to_notebook).

## Key Questions and Hypotheses:
1. **Is a country's happiness score correlated with its GDP per capita?**  
   *Hypothesis*: Countries with higher GDP per capita will exhibit higher happiness scores.

2. **Does predicted life expectancy influence happiness scores?**  
   *Hypothesis*: Countries with higher life expectancy will have higher happiness scores.

3. **Which continent is the happiest in 2023?**  
   *Hypothesis*: Significant differences exist in happiness scores across continents.

4. **How did global happiness change before, during, and after COVID-19 (2018–2024)?**  
   *Hypothesis*: Global happiness dropped during COVID-19, with specific countries like China showing more significant changes.

5. **Is there a correlation between unemployment rates and happiness?**  
   *Hypothesis*: Higher unemployment rates are associated with lower national happiness scores.

## Skills and Technologies Demonstrated:

### 1. **Data Collection and Cleaning**  
   - Combined multiple CSV files containing data on GDP, life expectancy, happiness scores, unemployment rates, and COVID-19 impacts into one cohesive dataset. This process is detailed in [`data_cleaning_combining.ipynb`](link_to_notebook).
   - Functions like `merge()`, `dropna()`, and `groupby()` were used to prepare the dataset efficiently.

### 2. **Main Analysis**
   - All statistical analysis, data visualizations, and insights are provided in [`main.ipynb`](link_to_notebook). This includes:
     - **Scatter Plot of Happiness Score vs GDP per Capita**
     - **Box Plot for Happiness Scores by Continent**
     - **Dual Axis Line Chart for GDP vs Happiness**
     - **Regression Analysis** and **ANOVA Testing**
     - **Comparative Analysis of COVID-19 Impact** (global happiness pre- and post-pandemic)

### 3. **Data Insights**
   - **GDP per capita**: Higher GDP per capita correlates moderately with higher happiness scores (R-squared ≈ 0.615).
   - **Life expectancy**: There is a significant positive correlation between life expectancy and happiness scores.
   - **Happiness across continents**: Oceania emerged as the happiest continent, with significant variations confirmed by ANOVA testing.
   - **COVID-19's Effect**: Global happiness scores were not significantly affected by the pandemic, but China showed a noticeable increase in happiness post-pandemic.


# Conclusion

In conclusion, economic factors significantly influence national well-being, with higher GDP per capita correlating moderately with higher happiness scores. There's potential correlation between unemployment rate and happiness, while a positive link exists between predicted life expectancy and happiness. Oceania had the highest median happiness score compared to the other continents. The COVID-19 pandemic didn't significantly alter global happiness scores, though China appeared to score a higher happiness score after COVID-19. 
