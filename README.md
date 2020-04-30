# COVID-19, Race, Ethnicity, and Income
Code and data for project on USA county-level COVID-19 infections, race, ethnicity, and income relationships

## Installation
This code uses the numpy, pandas, matplotlib, seaborn, and sklearn libraries for the Anaconda distribution of Python version 3.8.

## Project Motivation
This project uses the following USA county-level data to look at the impact of COVID-19 (Coronavirus Disease 2019) in racial and ethnic minority communities and the relationship to socioeconomic status:
* The number of COVID-19 cases and deaths through April 2020
* 2018 demographic data
* COVID-19 intervention data as of April 1, 2020
* CDC's 2018 social vulnerability index (SVI) data  

As an African-American, I was motivated to explore this topic after hearing several [reports](https://www.cdc.gov/coronavirus/2019-ncov/need-extra-precautions/racial-ethnic-minorities.html) stating that preliminary data showed that Black Americans were disproportionately affected by COVID-19.  I wanted to find out:
1.	Where are the counties with mostly Black or Hispanic populations?
2.	How do the COVID-19 numbers in counties with mostly Black or Hispanic populations compare to counties where Blacks and Hispanics are in the minority?
3.	Is there a relationship between COVID-19 and income?
4.	What factors relate to COVID-19 infection?

## File Descriptions
* **COVID19_County.ipynb** - the notebook which produced visualization files (.png) to explore and answer the above questions.
* **2018_CDC_SVI.csv** - CDC's 2018 County-level Social Vulnerability Index data
* **counties.csv** - 2018 County-level demographic data
* **interventions.csv** - COVID-19 intervention data
* **us-counties.csv** - data on number of COVID-19 cases and death by US county by date

## Results
The results of this code are available on my blog post located here: 
* The average number of COVID-19 cases and deaths per County in majority Black Counties is higher than the National Average
* The average number of COVID-19 cases and deaths per County is highest amongst the Nation's top 1% Highest Income Counties 
* The COVID-19 interventions of shutting down Public schools, shutting down Dine-in restaurants, and restricting the size of gatherings seem to have had the most impact on COVID-19.

## Licensing, Authors, Acknowledgements
The code here is free to use.  The data for this project was obtained from three different datasets available on Kaggle who must be given credit.  The licensing and other descriptive information about the datasets is available at the links below:
* **US counties COVID 19 dataset** (https://www.kaggle.com/fireballbyedimyrnmom/us-counties-covid-19-dataset)
* **2018 CDC's Social Vulnerability Index-US Counties** (https://www.kaggle.com/dannellyz/2018-cdcs-social-vulnerability-index-svi)
* **COVID-19 US County-level Summaries** (https://www.kaggle.com/jieyingwu/covid19-us-countylevel-summaries)
