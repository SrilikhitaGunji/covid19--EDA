This GitHub repository contains SQL queries and analysis for COVID-19 data. The provided SQL code is designed to work with a database named Covid_db and two tables: covid_deaths and covid_vaccination. These queries enable you to explore and analyze COVID-19 data, including cases, deaths, vaccinations, and population statistics.

--- Table of Contents
About
Data Import and Count
Important Columns
Duplicate Values Check
Continents and Countries
Average Number of Deaths per Day
Percentage of Population Infected (Top 10)
Highest Rate of Infection Relative to Population (Top 10)
Highest Number of Deaths by Country
Total World Deaths
Highest Number of Deaths by Continent
Rolling Average of New Vaccinations in Europe
---About
This project focuses on analyzing COVID-19 data using SQL queries. The provided queries cover various aspects of COVID-19 data, including data import checks, exploring important columns, checking for duplicates, calculating averages, and identifying the highest rates of infection and deaths.

---Data Import and Count
The initial section of the code checks whether the datasets have been successfully imported into the database and provides the count of records in each dataset.

---Important Columns
This section explores and retrieves important columns from the covid_deaths dataset, such as date, continent, location, total cases, new cases, total deaths, and population.

---Duplicate Values Check
The code checks for duplicate values in both the covid_deaths and covid_vaccination tables, ensuring data integrity.

---Continents and Countries
The code calculates the quantity of continents and countries present in the dataset, providing insights into the geographical distribution of the data.

---Average Number of Deaths per Day
This section calculates the average number of deaths per day for each location, considering continents and countries.

---Percentage of Population Infected (Top 10)
The code calculates the average percentage of the population infected with COVID-19 for the top 10 locations, helping to identify the most affected regions.

---Highest Rate of Infection Relative to Population (Top 10)
This section identifies the highest rates of infection relative to the population for the top 10 locations based on total cases.

---Highest Number of Deaths by Country
The code identifies the countries with the highest number of total deaths.

---Total World Deaths
This section calculates the total number of COVID-19 deaths worldwide, providing a global perspective on the pandemic's impact.

---Highest Number of Deaths by Continent
The code identifies the continents with the highest number of total deaths, helping to understand the regional distribution of COVID-19 fatalities.

---Rolling Average of New Vaccinations in Europe
The final section calculates the number of new vaccinations and the rolling average of new vaccinations over time for countries in the European continent.

Feel free to explore and utilize these SQL queries for your COVID-19 data analysis projects. Customize and extend the code as needed to suit your specific requirements.

Note: Ensure that you have set up the database and tables with the appropriate data before executing these queries.


