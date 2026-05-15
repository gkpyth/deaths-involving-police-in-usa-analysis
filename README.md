# Fatal Force — Police Killings in the United States

A data analysis project exploring fatal use of force by police in the United States, combining The Washington Post's fatal shootings database with US Census data on poverty, education, income, and racial demographics. Part of bootcamp personal projects portfolio.

## Features
- Exploratory data analysis across 5 datasets covering 2,500+ fatalities from 2015-2017
- Poverty rate and high school graduation rate analysis by US state
- Correlation analysis between poverty and education using regression and KDE plots
- Racial demographic breakdown by state using Census data
- Fatality analysis by race, gender, age, manner of death, and armed status
- Mental illness breakdown among victims
- Top 10 cities ranked by police killings
- Racial breakdown of killings in top 10 cities
- Choropleth map of police killings by US state
- Trend analysis of killings over time — annually and monthly
- Consistent color palette across all visualizations
- Markdown analysis cells with key findings after every chart

## Requirements
- Python 3
- Jupyter Notebook

## Installation
```
pip install -r requirements.txt
```

## How to Run
Open `Fatal_Force.ipynb` in PyCharm or Jupyter and run all cells top to bottom. Ensure all CSV files are placed in the `data/` folder before running.

## Project Structure
```
fatal-force-analysis/
├── Fatal_Force.ipynb          # Main analysis notebook
├── requirements.txt
├── README.md
└── data/                      # CSV files (not included in repo)
    ├── Deaths_by_Police_US.csv
    ├── Median_Household_Income_2015.csv
    ├── Pct_Over_25_Completed_High_School.csv
    ├── Pct_People_Below_Poverty_Level.csv
    └── Share_of_Race_By_City.csv
```

## Data Sources
- **Fatal Shootings Database** — The Washington Post has been tracking every fatal shooting by an on-duty police officer in the United States since January 1, 2015. Full database and methodology available at [washingtonpost.com](https://www.washingtonpost.com/graphics/investigations/police-shootings-database/).
- **US Census Data** — Poverty rate, high school graduation rate, median household income, and racial demographics sourced from the [US Census Bureau](https://factfinder.census.gov/faces/nav/jsf/pages/community_facts.xhtml).

## Limitations
- Fatal shootings data covers January 2015 to mid-2017 only — insufficient for long-term trend analysis
- Racial categories in Census data overlap (Hispanic is an ethnicity, not a race) causing some states to exceed 100% in demographic charts
- Weapon classifications in the fatalities dataset are self-reported by police departments and are inconsistent
- Race is unrecorded for ~7.7% of fatalities, which may affect racial disparity findings

## Author
Ghaleb Khadra