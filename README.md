# Global Population and Socioeconomic Insights - Tableau Project

## Overview

This Tableau project provides detailed insights into global population trends, fertility rates, and energy usage through various data visualizations. The project is divided into multiple interactive dashboards that explore the data from different perspectives, including population statistics by year, country, and continent, global fertility trends, and energy usage patterns.

The dashboards utilize historical data to project future trends and help policymakers and analysts make data-driven decisions.

## Key Features

- **Interactive Dashboards**: Explore global population trends, fertility rates, energy consumption, and other socioeconomic indicators.
- **Forecasting Models**: Population growth predictions based on historical data, with error intervals and trends.
- **Parameter Controls**: Dynamic parameter controls allow users to visualize multiple variables such as internet usage and energy consumption.
- **Geographical Maps**: Visualize data on a world map to understand country-specific and regional trends.
  
## Project Structure

```
/GlobalPopulationProject
    ├── Data/                   # Contains the dataset(s) used for the visualizations
    ├── Homework_2_Group_12.twb  # Tableau workbook with all visualizations and dashboards
    ├── README.md                # Project documentation
    └── Images/                  # Screenshots of key visualizations
```

### Files

- **`Homework_2_Group_12.twb`**: The Tableau workbook containing all dashboards and visualizations.
- **`Data/`**: Folder containing the data files used in the Tableau project.
- **`Images/`**: Folder containing screenshots for previewing the dashboards in the README file.

## Data Sources

This project uses various global datasets on population and socioeconomic indicators. The datasets include:

- **Global Population Data**: World population by year, country, and continent.
- **Fertility Rate Data**: Fertility rates by region and year.
- **Energy Usage Data**: Data on energy consumption by country and continent.

## Visualizations and Dashboards

### Global Population Insights

This dashboard provides a comprehensive view of global population trends:

- **Bar Graph**: Shows the world population from 2013 to 2023, highlighting the steady increase in population.
- **Continent-Wise Population**: A bar chart comparing the population of different continents in 2023.
- **World Map**: A map that displays the population distribution across countries in 2023.
- **Forecasting Model**: A time-series chart predicting world population growth up to 2030, using an additive trend model with confidence intervals.

![Global Population Insights](Images/dashboard1.png)

### Global Fertility Trends and Female Population Statistics

This dashboard focuses on global fertility rates and the female population:

- **Fertility Rate by Year**: Displays the average fertility rate from 2008 to 2022.
- **Continent-Wise Fertility Rate**: A bar chart comparing the fertility rates of different continents in 2022.
- **Female Population Percentage Map**: A geographical map showing the female population percentage by country.
- **Fertility Trends by Country**: Time-series data showing the changes in female population percentage in various countries over time.

![Global Fertility Trends](Images/dashboard2.png)

### Global Socioeconomic and Environmental Indicators

This dashboard allows for the exploration of various socioeconomic indicators:

- **Bar Chart**: Visualizes total internet users by country for 2022.
- **World Map**: Displays selected socioeconomic and environmental indicators on a world map.

![Global Socioeconomic Indicators](Images/dashboard3.png)

### Female Population Dashboard

This dashboard explores female population trends across various countries and regions, with a focus on Russia's female population statistics.

- **Bar Chart**: Shows the female population percentage globally, along with continent-wise comparisons.
- **Time-Series Analysis**: Female population trends from 2008 to 2023.

![Female Population Dashboard](Images/dashboard4.png)

## Forecasting

The forecasting model uses an additive trend approach to predict future population growth with a prediction interval of 95%. The Mean Absolute Percentage Error (MAPE) is 32%, which suggests reasonable accuracy in the population predictions up to 2030.

## Insights

- **Global Population Growth**: The world population is projected to reach 8.59 billion by 2030, with most of the growth coming from Asia and Africa.
- **Fertility Trends**: Africa has the highest fertility rate, while Europe has the lowest. The global average fertility rate has been declining over the past 15 years.
- **Female Population**: Russia has consistently maintained the highest female population percentage since 2008.
- **Socioeconomic Indicators**: Internet usage varies significantly by country, with high penetration in regions such as North America and Europe.


Let me know if you need any further assistance!
