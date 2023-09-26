# Project_1
Data Analytics Bootcamp: Project 1

## Table of Contents
1. [Outline](#outline)
2. 

# Outline
The World Happiness Report, a publication by the Sustainable Development Solutions Network, driven by Gallup World Poll data, underscores the growing global demand for prioritizing happiness and well-being as key governmental benchmarks. This report explores current global happiness levels and delves into how the science of happiness elucidates variations in personal and national happiness.

Our project aims to delve into the multifaceted factors that influence happiness worldwide, considering economic, social, cultural, and population indicators. To achieve this, we will conduct an exploratory data analysis (EDA) using the data available on Kaggle 

We utilized a total of seven CSV files, each corresponding to a specific year spanning from 2015 to 2020, alongside an additional CSV file dedicated to capturing COVID-related outcomes specifically for the year 2020.

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






















