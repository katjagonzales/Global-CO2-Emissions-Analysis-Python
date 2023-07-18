# Global-CO2-Emissions-Analysis-Python
Analysis of global CO2 emissions data conducted in Python using machine learning techniques as part of the CareerFoundry Data Analytics program.

## Project Overview
The purpose of this project was to source a data set of my own choice and define key questions to perform a data analysis utilizing Python. 

I chose a dataset that includes measurements on CO2 emissions (annual, per capita, cumulative and consumption-based), other greenhouse gases, energy mix, and other relevant metrics for the years 1750 – 2021.

My goal was to look into the distribution of CO2 emissions and key factors, focusing on:
-  Exploring relationships between CO2 emissions and other variables.
-  Identifying countries that produce the highest CO2 emissions.
- Investigating different sources of energy and respective levels of emissions.

## Data
The dataset is publicly disclosed open data collected by [Our World in Data](https://ourworldindata.org/co2-and-greenhouse-gas-emissions).

I downloaded it on GitHub. The CO2 and Greenhouse Gas Emissions dataset is updated regularly and is built upon a number of datasets and processing steps.

Here are the links to download the CO2 Emissions dataset, the time-series dataset (only used in script 6.6) and the JSON file used for the geospatial analysis:

[CO2 and Greenhouse Gas Emissions dataset](https://github.com/owid/co2-data)

[Carbon Dioxide (CO2) Emissions - USA](https://data.nasdaq.com/data/BP/C02_EMMISSIONS_USA-carbon-dioxide-co2-emmissions-usa)

[Country Polygons as GeoJSON](https://datahub.io/core/geo-countries#data)

## Folders
Here is a short description of the folder contents in this repository:

**01. Documentation**: contains the following PDF files: 
- **A6 Project brief:** includes the criteria and limitations of the project. Guidelines were provided by CareerFoundry
- **Data Profile:** An overview including the wrangling steps, consistency checks, the data dictionary and my initial research questions

**02. Data**: contains two subfolders:
- **Original Data:** includes the original csv file (owid-co2-data) and the JSON file used for geospatial analysis
- **Prepared Data:** includes the different versions of the dataframe as pkl files.
  The last version is also available as a csv file (needed to create visualizations in Tableau)

**03. Scripts**: contains all Python scripts (Jupyter Notebook). Please note that script 6.3 couldn't be uploaded (not even in a compressed version) because of the max file size limitation of GitHub.

**04. Visualizations**: contains the visualizations for the project created in Python. Please note that most visualizations were created in the final phase of the project, utilizing Tableau.

## Deliverables
The most relevant results of this case study can be viewed as an interactive storyboard on [Tableau](https://public.tableau.com/app/profile/katja.gonzales/viz/GlobalCO2EmissionsAnalysis_16875266911180/DataStory)

## Tools
- *Tableau*

- *Python* using the following libraries:
  * pandas
  * numpy
  * os
  * seaborn
  * matplotlib
  * scipy
  * folium
  * json
  * sklearn
  * pylab
  * quandl
  * statsmodels
  * datetime
