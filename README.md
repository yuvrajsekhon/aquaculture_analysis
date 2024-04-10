# Data Analysis for Aquaculture Production and Wealth per capita

## Description

This project utilises publicly available datasets from the World Bank to analyse the relationship between aquaculture fish production in kg per capita and GDP per capita in USD.

## Data Sources

The datasets used in this project are sourced from the World Bank's official website and include the following indicators:

- **Aquaculture fish production (metric tons)**: `ER.FSH.AQUA.MT`
- **GDP per capita (USD)**: `NY.GDP.PCAP.CD`
- **Population total**: `SP.POP.TOTL`

Direct links to the datasets:
- [Aquaculture Production](https://data.worldbank.org/indicator/ER.FSH.AQUA.MT): [Download CSV](https://api.worldbank.org/v2/en/indicator/ER.FSH.AQUA.MT?downloadformat=csv)
- [GDP per Capita](https://data.worldbank.org/indicator/NY.GDP.PCAP.CD): [Download CSV](https://api.worldbank.org/v2/en/indicator/NY.GDP.PCAP.CD?downloadformat=csv)
- [Population Total](https://data.worldbank.org/indicator/SP.POP.TOTL): [Download CSV](https://api.worldbank.org/v2/en/indicator/SP.POP.TOTL?downloadformat=csv)

For the final analysis, the datasets labeled with `aquaculture_analysis_cleaned` are used, including:
- [Aquaculture fish production in kg per capita](aquaculture_analysis_cleaned_PRODUCTION_PER_HEAD_1999_2019.csv)
- [GDP per capita](aquaculture_analysis_cleaned_GDP_PER_HEAD_1999_2019.csv)

To determine the aquaculture fish production per capita, we started with the base [production figures for each country and year](aquaculture_analysis_cleaned_PRODUCTION_1999_2019.csv). By dividing these figures by the respective [population numbers](aquaculture_analysis_cleaned_POPULATION_1999_2019.csv), we calculated the production on a per capita basis, reflecting the amount of fish produced per person.
