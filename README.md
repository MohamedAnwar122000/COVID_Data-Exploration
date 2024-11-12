# COVID-19 Data Exploration Project

## Project Purpose
This project analyzes COVID-19 data to gain insights into infection rates, death rates, vaccination progress, and regional variations. By examining metrics like total cases, deaths, and vaccinations over time and across countries and continents, this project aims to highlight the pandemic's impact globally and locally.

## Dataset
The project uses two primary datasets:

1. **CovidDeaths**: Records of COVID-19 cases, deaths, and population data by country, date, and continent.
2. **CovidVaccinations**: Data on new vaccinations administered by country and date.

These datasets enable analysis of infection and mortality rates as well as vaccination coverage.

## Questions Answered

1. **What is the likelihood of dying if infected by COVID-19 in a specific country?**
   - Calculates death percentage by comparing total deaths to total cases in each country.
2. **What percentage of the population has been infected?**
   - Compares total cases to population to understand infection rates per country.
3. **Which countries have the highest infection rate relative to their population?**
   - Identifies countries with the highest infection percentages.
4. **Which countries have the highest death count per population?**
   - Highlights the mortality impact per population by country.
5. **Which continents report the highest COVID-19 death counts per population?**
   - Aggregates data by continent for regional comparison.
6. **What is the percentage of the population vaccinated in each country?**
   - Combines cumulative vaccination counts with population data to estimate vaccination coverage.

## Skills and Techniques Used

- **Joins** to integrate multiple data sources
- **CTEs** for organizing complex queries
- **Window Functions** for calculating rolling totals
- **Aggregate Functions** to summarize key metrics
- **Views** for reusable data preparation
- **Data Type Conversion** to handle numeric operations on text-based fields

This structure enables a comprehensive exploration of COVID-19's spread, severity, and vaccination progress globally and by region.
