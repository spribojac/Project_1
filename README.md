# Project_1
Data Analytics Bootcamp: Project 1

## Table of Contents
1. [Outline](#outline)
2. [Data Cleaning](#data_cleaning)
3. [Happiness Scores from 2015 to 2020](Happiness_Scores_from_2015_to_2020)

# Outline
The World Happiness Report, a publication by the Sustainable Development Solutions Network, driven by Gallup World Poll data, underscores the growing global demand for prioritizing happiness and well-being as key governmental benchmarks. This report explores current global happiness levels and delves into how the science of happiness elucidates variations in personal and national happiness.

Our project aims to delve into the multifaceted factors that influence happiness worldwide, considering economic, social, cultural, and population indicators. To achieve this, we will conduct an exploratory data analysis (EDA) using the data available on Kaggle to answer the following question:

_"What were the pivotal factors shaping societal well-being between 2015 and 2020, and how did these factors evolve in response to the unique challenges posed by the COVID-19 pandemic in 2020?"_

We utilized a total of seven CSV files, each corresponding to a specific year spanning from 2015 to 2020, alongside an additional CSV file dedicated to capturing COVID-related outcomes specifically for the year 2020.

# Data Cleaning
We began by importing and processing each csv file for each year. The dataset contains information about happiness scores, GDP per capita, social support, healthy life expectancy, freedom, generosity, and corruption.

We standardized column names across all CSV files, ensuring ease of access and reference for the team. Each cleaned CSV file was named according to the respective year.

The 2020 file needed to be processed seperately to drop additional columns to enable it to follow the format of the previous files.

# Happiness Scores from 2015 to 2020
## Global Visualisation

### Global Happiness in 2015
![globe_happiness_score_map_2015](https://github.com/spribojac/Project_1/assets/65559564/0403d28a-341f-4836-9104-e6421eece197)

### Global Happiness in 2016
![globe_happiness_score_map_2016](https://github.com/spribojac/Project_1/assets/65559564/29af777c-dc7f-4490-9838-f2210000974d)

### Global Happiness in 2017
![globe_happiness_score_map_2017](https://github.com/spribojac/Project_1/assets/65559564/83877c6e-6a7a-4398-987a-f3568f57164e)

### Global Happiness in 2018
![globe_happiness_score_map_2018](https://github.com/spribojac/Project_1/assets/65559564/bce6619f-160e-439a-a463-186b11f5e45d)

### Global Happiness in 2019
![globe_happiness_score_map_2019](https://github.com/spribojac/Project_1/assets/65559564/351ce401-6416-46d0-866c-adbca3702900)

### Global Happiness in 2020
![globe_happiness_score_map_2020](https://github.com/spribojac/Project_1/assets/65559564/0a6c0557-c4d9-4fbb-bac5-222fd707c7f0)

Analyzing happiness scores regionally and across continents over the years reveals interesting trends. The color spectrum, ranging from green (indicating higher happiness) to red (representing lower happiness), highlights notable patterns. 

Consistently high happiness scores are observed in North America, South America, Australia, and Europe. These regions often have stable economies, strong social support systems, and high levels of personal freedom, all of which are associated with higher levels of happiness.

The presence of red and orange shades in the African continent, particularly in the central belt, aligns with the challenges many African countries face, including issues related to political instability, poverty, and limited access to healthcare and education. Additionally, conflict zones like Syria, Afghanistan, and Iraq have experienced significant declines in happiness due to the impact of wars and violence on the well-being of their populations.

South Asia generally scores lower than its Southeast Asian counterparts, while Eastern Asia maintains a steady average happiness score of around 5, which may reflect the influence of cultural and societal norms.
In Europe, Western European countries consistently score high in happiness, thanks to robust economies and social safety nets. Central and Eastern European nations have made progress since the end of the Cold War, though some, like Ukraine, Bulgaria, and Georgia, still report scores averaging between 4 and 5.

## Mean Happiness Scores from 2015 to 2020
![mean_happiness_score_all_years](https://github.com/spribojac/Project_1/assets/65559564/07d193e2-739e-470d-a81e-fb26f29b9abd)

### Mean Happiness Score with 95% confidence intervals
![mean_change_Happiness Score](https://github.com/spribojac/Project_1/assets/65559564/e7796282-af9a-42b3-b8b3-68ba7bfa1ff0)

The most notable trend of the happiness score over 2015 to 2020 is it’s stability. Looking at the line graph above the mean Happiness Score has remained relatively stable over the years, with slight fluctuations, mainly in the years 2019-2020 where a very small increase in the Happiness score can be seen. The mean Happiness Score across these six years hovers around 5.38. 

The lowest observed Happiness Score during this period was 2.5669, emphasizing moments of profound unhappiness, while the highest score reached an impressive 7.8087, both in the year 2020, underscoring the capacity for exceptional well-being.

This stability emphasizes the resilience of overall happiness and the need for a holistic approach to improving well-being that goes beyond single indicators.

## Contribution of other variables to Happiness Score
![combined_mean_line_plot_all_years](https://github.com/spribojac/Project_1/assets/65559564/1f32118f-a596-48aa-a7da-27821fd4a7d5)

### Mean GDP per Capita with 95% confidence intervals
![mean_change_GDP per Capita](https://github.com/spribojac/Project_1/assets/65559564/4aba91b8-7e22-4531-a490-33c1b98ee326)

GDP per Capita, an indicator of economic prosperity, shows a consistent positive correlation with the Happiness Score. Countries with higher GDP per Capita generally report higher happiness levels. Over the six years, there is a general upward trend in GDP per Capita, indicating global economic growth. However, the rate of increase varies from year to year. High-ranking countries have GDP per Capita values typically above 1.3, while low-ranking countries often have values below 0.5, demonstrating the strong link between economic prosperity and happiness.

### Mean Social Support with 95% confidence intervals
![mean_change_Social Support](https://github.com/spribojac/Project_1/assets/65559564/cc076983-d0ab-4306-9c66-c91b0bfc0b8c)

Social Support, which measures the presence of strong social networks, demonstrates a strong positive correlation with the Happiness Score. Nations with robust social support structures tend to have happier populations. While there are some minor fluctuations, the mean Social Support remains relatively consistent, suggesting the enduring importance of social networks in promoting well-being.

### Mean Health/Life Expectancy with 95% confidence intervals
![mean_change_Life Expectancy_Health](https://github.com/spribojac/Project_1/assets/65559564/aa72ee30-859c-40e8-ab50-6c93c7c6b4f8)

Life Expectancy/Health, an indicator of overall health and access to healthcare, positively influences happiness. Countries with better health outcomes report higher happiness scores. Over the years, there is a slight overall increase in Life Expectancy/Health, which aligns with global improvements in healthcare access and life expectancy. High-ranking countries have life expectancies around 0.9 or higher, while low-ranking countries have life expectancies often well below 0.3, emphasizing the importance of health in happiness.

### Mean Freedom with 95% confidence intervals
![mean_change_Freedom](https://github.com/spribojac/Project_1/assets/65559564/30998fc0-f313-4fb0-8065-a90571faaf32)

Freedom, representing personal liberties and civil rights, shows a consistent positive correlation with happiness. Nations with greater freedoms tend to have higher happiness scores. While there are minor fluctuations, the overall trend in Freedom remains relatively stable across the years. High-ranking countries exhibit high levels of freedom (e.g., Switzerland with 0.66557), while some low-ranking countries have lower freedom scores (e.g., Chad with 0.23501).

### Mean Trust in Goverment with 95% confidence intervals
![mean_change_Trust (government corruption)](https://github.com/spribojac/Project_1/assets/65559564/94bb2d0b-6603-42f1-b546-909c87de228b)

Trust in Government, which reflects the perception of government integrity, negatively correlates with happiness. Countries with lower levels of trust in government tend to report lower happiness scores. Over the years, Trust in Government Corruption experiences slight fluctuations, reflecting shifts in public perception of government integrity. Trust in government varies significantly but is generally moderate to high in top-ranking countries (e.g., Switzerland with 0.41978) and often lower in low-ranking countries (e.g., Chad with 0.05269).

### Mean Generosity with 95% confidence intervals
![mean_change_Generosity](https://github.com/spribojac/Project_1/assets/65559564/1720c8c5-ba3e-4900-a291-8698f036e6c8)

Generosity, measuring charitable behaviour and giving, exhibits a more mixed relationship with the Happiness Score. While there is often a positive correlation, it is weaker and less consistent than other factors. Generosity levels show minor variations over the years, suggesting that its impact on overall happiness may be less pronounced compared to factors like social support or health. Generosity levels vary but are generally moderate to high in both top and bottom countries (e.g., Switzerland with 0.29678, Chad with 0.18386), indicating a willingness to contribute to well-being.

## Final Thoughts
In summary, this analysis provides valuable insights into societal well-being from 2015 to 2020. Variables such as GDP per Capita and social support consistently exert positive influences on happiness, while trust in government corruption and generosity reveal more nuanced relationships. The relationships between these variables will be explored in the remainder of this report.

------------------------------------------------------------------------------------------------------

# Conclusion and Final Thoughts - COVID Report

In this analysis, we explored the intricate relationship between various socio-economic factors and their potential impact on handling the COVID-19 pandemic. Let's recap our key findings:

## GDP and Happiness:

We found a significant association between a country's GDP and its reported happiness. Countries with higher GDP tend to have a more favorable happiness score.

## GDP and Social Support:

WE found that there is no significant association between the GDP and Social Support .Countries with higher GDP tend to have a less Social Support.

## Happiness Score and Generosity:

WE found that there is no significant association between the Happiness Score  and Generosity .Countries with higher Happiness Score tend to have a less Generosity.

## Government Corruption Perception:

Countries with a lower perception of government corruption were likely to have a more positive outlook on happiness, suggesting the importance of transparent and accountable governance.

## Life Expectancy and COVID-19:

Although not directly analyzed in this dataset, life expectancy is a vital indicator of overall health and well-being, likely affecting how countries handle the pandemic.

## Social Support and COVID-19:

Strong social support seems to correlate with better compliance with preventive measures, potentially contributing to lower COVID-19 transmission rates.

While GDP, corruption perception, life expectancy, and social support are vital factors, managing a pandemic like COVID-19 is a multidimensional challenge. It requires a holistic approach, considering healthcare infrastructure, public health policies, education, cultural factors, and more.

Understanding these relationships is crucial for policymakers and public health experts in crafting effective strategies to combat the current pandemic and future health crises. By addressing these factors, we can work towards a more resilient and healthier global community.

---

## Graphs Overview:

- **Scatter Plot: GDP vs. Happiness**
  - Showed the positive correlation between a country's GDP and reported happiness.

- **Box Plot: Happiness Distribution by Corruption Perception**
  - Illustrated the relationship between corruption perception and happiness scores.

- **Heatmap: Correlation Matrix**
  - Displayed the correlation coefficients among the variables in the dataset.

- **Geo Plots: Healthy Life Expectancy and COVID-19 Cases**
  - Explored the geographical representation of life expectancy and COVID-19 cases.

---

By analyzing these aspects, we gain valuable insights into the complexities of managing a global health crisis like COVID-19 and can develop more informed strategies for a healthier and happier society.

##########################################################################################################################################################################################################

# COVID19 Death / Happiness Report Data Analysis

In this project, we perform an in-depth analysis of COVID-19 death data alongside happiness report data from different countries. Our goal is to explore potential relationships and insights between the COVID-19 pandemic's impact on countries and their citizens' reported happiness.

## Table of Contents
1. [Introduction](#introduction)
2. [Data Import](#data-import)
3. [Data Visualization](#data-visualization)
4. [Correlation Analysis](#correlation-analysis)
5. [Conclusion](#conclusion)

---

## Introduction

The year 2020 brought unprecedented challenges to the world, primarily due to the COVID-19 pandemic. While the pandemic itself had a direct impact on public health, it also had indirect consequences on various aspects of society, including people's overall well-being and happiness. This analysis aims to shed light on the relationship between the severity of COVID-19 outbreaks in different countries and their respective happiness levels.

---

## Data Import 

### COVID-19 Death Dataset

We start by importing and preprocessing the COVID-19 death dataset. The dataset contains information about COVID-19 deaths in various countries and regions. We clean and aggregate the data to make it suitable for analysis.

### Worldwide Happiness Report

Next, we import the Worldwide Happiness Report, which includes happiness scores and various factors contributing to happiness, such as GDP per capita, social support, healthy life expectancy, and freedom to make life choices. We also clean and prepare this dataset for analysis.

---

## Data Visualization <a name="data-visualization"></a>

### COVID-19 Death Progression in Specific Countries

We begin our analysis by visualizing the progression of COVID-19 deaths in specific countries. The graph below illustrates the death toll over time for selected countries, offering insights into how the pandemic evolved in different regions.

![COVID-19 Deaths](images/covid_time.png)

### Rate of COVID-19 Death Curve

To understand the rate of change in COVID-19 deaths, we present the death rate curve. This curve shows how quickly or slowly COVID-19 deaths increased in specific countries, allowing us to identify trends and critical periods.

![Death Rate Curve](images/difference_time.png)

### Maximum COVID-19 Death Rate

We identify and list the maximum death rates observed for specific countries. This information provides a glimpse into the most challenging periods these countries faced during the pandemic.

### Scatter Plot: Correlation between Covid19 Deaths and Happiness KPIs

Moving beyond COVID-19 data, we explore the correlation between GDP per capita and happiness scores. The scatter plot below illustrates this relationship, highlighting how economic prosperity might influence people's happiness.

![GDP vs Covid](images/gdp_covid.png)
![Healthy Life vs Covid](images/healthy_life_covid.png)

---

The correlation values provide insights into how these factors might influence the severity of COVID-19 outbreaks in different countries.

---

## Conclusion

This analysis offers a comprehensive look at the interplay between the COVID-19 pandemic and happiness levels across different countries. By visualizing COVID-19 death progression, identifying critical periods, and exploring correlations with various factors, we aim to contribute to a better understanding of the pandemic's broader impact on societies.

Feel free to further explore the data and analysis in the accompanying Jupyter Notebook.






















