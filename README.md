# Global Population, Socioeconomic, and Energy Insights - Tableau Project

## Overview

This Tableau project offers a comprehensive analysis of global population trends, fertility rates, and energy usage through interactive and detailed dashboards. The project leverages multiple data sets to provide insights into global demographics, fertility statistics, and energy consumption patterns. Through various visualizations, the project uncovers trends and forecasts for future global changes, helping policymakers, researchers, and analysts make data-driven decisions.

## Key Features

- **Population Analytics**: Analyze global population data by year, continent, and country.
- **Fertility and Demographics**: Explore fertility rates and female population statistics by country and region.
- **Energy Consumption Trends**: Examine global energy use patterns over time, by region and country.
- **Forecasting Models**: Predict population trends up to 2030 using time series models with error intervals and accuracy measures.
- **Dynamic Interaction**: Use interactive filters and parameters to explore multiple socio-economic variables.

## Project Structure

```
/Global_Population_Insights_Project
    ├── Data/                    # Contains the datasets used for the visualizations
    ├── Global Population, Socioeconomic, and Energy Insights/ # The Tableau workbook with all visualizations and dashboards
    ├── README.md                 # Project documentation
    └── Images/                   # Screenshots of the Tableau dashboards
```

## Data Sources

The project uses the following datasets:

- **Global Population Data**: Historical population statistics from 2000 to 2023, projected up to 2030.
- **Fertility Data**: Fertility rates across various regions and countries, along with demographic statistics for female populations.
- **Energy Consumption Data**: Data on energy consumption by region and per capita energy usage for selected countries.
Here's the updated section of your `README.md` file that includes a detailed explanation of the parameter usage with coding:

## Dynamic Parameters for Socioeconomic Indicators

This project utilizes a parameter-driven approach to explore multiple socioeconomic indicators dynamically. The parameter control allows users to select different variables and view their corresponding visualizations. These parameters are coded in the dashboard to make the analysis highly interactive and customizable based on the user’s interest.

### Available Parameters

- **Internet Users Percentage**: Displays the percentage of internet users in relation to the total population for each country.
- **Total Internet Users**: Shows the absolute number of internet users by country.
- **CO2 Emissions per Capita**: Visualizes carbon dioxide emissions on a per-person basis by country.
- **Total CO2 Emissions**: Displays the total CO2 emissions by country.
- **Electrical Power Consumption per Capita**: Shows the electrical power consumption per capita in different countries.
- **Total Electrical Power Consumption**: Displays the total electrical power consumed by each country.
- **Life Expectancy**: Illustrates the average life expectancy by country, offering insights into health and longevity trends.
- **Mortality Rate Under 5**: Shows the under-5 mortality rate by country, providing insights into public health conditions.

### Parameter Implementation

The parameter allows users to dynamically change the measure they want to explore. By switching the parameter, the corresponding bar charts and maps in the **Global Socioeconomic and Environmental Indicators Dashboard** will update to reflect the selected variable. This feature makes the dashboard flexible for different types of analysis without needing to manually adjust the underlying data.

For example:
- When **"Total Internet Users"** is selected, the map and bar graph will display the absolute number of internet users per country.
- When **"CO2 per Capita"** is selected, the visualization updates to show CO2 emissions per capita.

This coding was implemented using calculated fields in Tableau, enabling real-time changes across the dashboard without additional manual filtering. The flexibility provided by parameters enhances the usability of the dashboard for multiple analyses within a single view.

## Visualizations and Dashboards

### Global Population Insights

This dashboard provides a detailed analysis of global population trends and projections:

- **Population Growth Over Time**: A bar graph showing the population of the world from 2013 to 2023, illustrating a steady increase.
- **Continent-Wise Population Distribution**: A bar chart comparing population totals across continents in 2023, highlighting Asia’s dominance.
- **Country-Level Population**: A geographical map that visualizes population distribution across various countries in 2023.
- **Population Forecasting Model**: A time-series graph that forecasts world population growth up to 2030, using additive trend modeling and confidence intervals.

### Global Fertility Trends and Female Population Statistics

This dashboard explores fertility rates and female population statistics across the globe:

- **Fertility Rate Trends**: A line chart displaying the global average fertility rate from 2008 to 2022, showing a declining trend.
- **Fertility Rate by Continent**: A bar chart comparing fertility rates across continents in 2022, with Africa leading and Europe at the lowest.
- **Female Population Percentages**: A map visualizing the percentage of the female population by country.
- **Longitudinal Female Demographics**: Time-series data showcasing the evolution of the female population percentage across various countries over time.

### Global Energy Use Insights

This dashboard analyzes energy consumption patterns globally, with a focus on regional disparities:

- **Energy Use Trends**: A bar graph that shows the global per capita energy use from 2008 to 2023, with notable decreases in recent years.
- **Energy Consumption by Country**: A geographical map comparing energy use per capita across countries, highlighting differences in development and resource access.
- **Energy Use by Continent**: A comparative bar chart showing energy use per continent, with Europe and Asia leading in consumption.
- **Trends Over Time**: A line chart showing the energy use trends of key countries such as Qatar, the U.S., and Iceland.


### Global Socioeconomic and Environmental Indicators

This dashboard allows users to explore various socioeconomic indicators dynamically:

- **Multiple Variable Visualizations**: A bar graph visualizing multiple socioeconomic indicators like total internet users across different countries.
- **Geographical Map**: A world map showing selected socioeconomic indicators, allowing users to compare global disparities.

### Female Population Trends

This dashboard highlights the trends in female population percentages across different regions:

- **Country-Level Female Population**: A bar graph displaying the female population percentage globally, highlighting Russia's consistently high female population percentage over the past 15 years.
- **Trends by Continent**: A comparison of the female population trend across continents, showing slight but steady increases over time.

## Forecasting

- **Forecasting Model**: The project includes a predictive model that uses an additive trend to forecast world population growth up to 2030. The model has a Mean Absolute Percentage Error (MAPE) of 32%, indicating the accuracy of the projections.
  
## Insights and Key Findings

1. **Global Population Growth**: The world population is projected to reach 8.59 billion by 2030, with the majority of growth occurring in Asia and Africa.
2. **Fertility Decline**: The global fertility rate has been declining steadily, particularly in Europe and North America, while Africa maintains a higher average.
3. **Female Population**: Russia has consistently maintained the highest female population percentage globally for the past 15 years.
4. **Energy Use Patterns**: While Europe and Asia lead in energy consumption, energy use per capita has declined globally due to advancements in energy efficiency and the adoption of alternative energy sources.
5. **Socioeconomic Disparities**: Significant socioeconomic disparities exist globally, with internet usage and energy consumption reflecting the divide between developed and developing nations.

