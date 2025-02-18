# Covid Vaccine Adverse Reaction Analysis 2020-2024

## Introduction
This project analyzes adverse reactions to vaccines using a dataset that includes patient demographics, vaccine manufacturers, geographic distribution, and gender-based reactions. The analysis aims to identify trends in adverse reactions and fatalities associated with vaccinations.

## Table of Contents
- [Introduction](#introduction)
- [Age Analysis](#1-age-analysis)
- [Vaccine Manufacturer Analysis](#2-vaccine-manufacturer-analysis)
- [Location Analysis](#3-location-analysis)
- [Gender Analysis](#4-gender-analysis)
- [Summation](#summation)
  

## Objective

1. Determine the impact vaccines have on males and females. 

2. Establish if any states have a higher risk of an adverse or death event.

3. Learn which, if any, vaccine manufacturer has a higher risk for an adverse or death event. 

4. Discover trends on an age basis and determine which groups are more at risk. 

## Notebooks  

1. **Gender Analysis (`gender_analysis.ipynb`)**  
   - Examines the gender distribution in the data.  
   - Includes visualizations and insights based on gender-based data.


![Gender Image](./Images/gender_distribution.png)
![Death Image](./Images/gender_death_rate.png)


2. **Location Analysis (`location_analysis.ipynb`)**  
   - Analyzes geographical data and trends.  
   - Includes visualizations and insights based on location-based data.

3. **Vaccine Manufacturer Analysis (`vac_manu_analysis.ipynb`)**  
   - Evaluates data related to vaccine manufacturers.  
   - Compares production, distribution, and other relevant metrics.  

4. **Age Analysis (`age_analysis.ipynb`)**  
   - Examines age distribution data.  
   - Identifies trends and patterns across different age groups.  

## Dataset

VAERSDATA1 (3).csv – The primary dataset containing vaccine adverse event data, sourced from VAERS (Vaccine Adverse Event Reporting System). 

## Requirements  

Ensure you have the following dependencies installed before running the notebooks:  

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

## Usage

Open the notebooks using Jupyter"

```bash
jupyter notebook
```

Select the notebook you want to run and execute the cells in order.

## Team Members 

William Robertson, 
Sandra Salazar, 
Lance Cannon, 
Eli Crawley, 
Luke Roberts

## Data Sources

Vaccine Adverse Event Reporting System. 2024. VAERS 
https://vaers.hhs.gov/ 

COVID-19 World Vaccine Adverse Reactions - Ayush Garg. 2024 
https://www.kaggle.com/datasets/ayushggarg/covid19-vaccine-adverse-reactions?resource=download&select=VAERSVAX.csv 

Centers for Disease Control and Prevention. 2023. "COVID-19 Vaccine Effectiveness." CDC. 
https://www.cdc.gov/coronavirus/2019ncov/vaccines/effectiveness.html 

OpenAI. "ChatGPT-generated content about vaccine statistics." ChatGPT, 6 Feb. 2024 
https://openai.com 
