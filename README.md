<img src="https://www.bochum.de/C125830C0042AB74/CurrentBaseLink/W2BMMFEF129BOCMDE/$FILE/corona_3d_slider_ContentHalf.jpg" alt="Coronavirus :(" width="100"/>

# Flying with corona
*[Shelley Obery, Kyrian Bourgi, Mikki Seidenschnur]*

*[data analytics, Berlin, June 2020]*

## Content
- [Project Description](#project-description)
- [Questions & Hypotheses](#questions-hypotheses)
- [Dataset](#dataset)
- [Database](#database)
- [Workflow](#workflow)
- [Organization](#organization)
- [Links](#links)

## Project Description
In January 2020, disaster struck, and the first case of the corona virus (COVID-19) was registrered outside the point of origin in Wuhan, China. It became apparent the current availbility of air travel had enabled an exponential spread of the deadly respiratory virus. As a direct response to contain the virus the German airline Lufthansa decreased the flights with 95% from the 19th of March.

Studies suggest that the aviation industry is responsible for 2.4% of the total greenhouse gas emission [[Graver, Zhang, Rutherford](https://theicct.org/sites/default/files/publications/ICCT_CO2-commercl-aviation-2018_20190918.pdf)]. 

## Questions & Hypotheses
Following the extreme decline in air traffic, it seems interesting to make a correlation study, trying to prove/disporve the following hypothesis:

1. The aviation industry plays a major role in the total emission of greenhouse gasses on planet earth. This would suggest that the decrease in air traffic has caused a lower pollution level in general.

2. Covid-19 impacted cryptocurrencies positively 

3. Quarantine measure benefited new innovative businesses market players that have digitalized processes.

## Dataset
We have collected various datasets: 

1. Pollution Data / Flights scheduled data

We started of by collecting world pollution data that we have gathered from the world air quality index API, as well as data on the scheduled & tacked flights. We have created visualisations to contrast the correlation between pollution and flights.


2. Cryptocurrency Data

We have gathered data on cryptocurrency market, more specifically Bitcoin as most of the other cryptocurrencies are correlated to it. We have found out that there has been an increase/recovery of BTC during the quarantine. However we cannot say if this is an increase in value or if this is just the market recovering from the previous trends.

3. Zoom Data

Finally as with the quarantine measures and the switch to home-office we wanted to be able to put into evidence the impact of this kind of measures on company stocks. While most of the stock listed companies have seen their values decreasing. Zoom entered the market with the competitive advatange of offering both video conferences as well as "Teamviewer-like"-features. From the data collected from Yahoo Finance API and the graph we have created, it is apparent that the price of Zoom reached three times the original value at the beginning of the quarantine. We believe the home-office trend played a big role in this huge rise of value.

## Database
Our data base is strucutred as follows: we have one table that contains pollution data that is related to the tables of flights tracked / cancelled, a second table for cryptocurrency data and finally Zoom stocks prices table.

## Workflow
1st day: We did some research on potentially interesting research topic and which questions we would like to answer. 
2nd day: We agreed on the topic and have split the datasets to be collected between us so we will achieve a satisfactory on-time-delivery.
3rd day: All the data had been collected through, and the remaining work consisted mostly of cleaning code and preparing the presentation material.

## Organization
We organized our work using Trello you can find more informations on the work process here: 

Our repository contains a folder called "data" which contains all the data we have collected and a second one called "modules" that includes all codes we have created to perform analysis. 

## Links
[Repository](https://github.com/https://github.com/MikkiSeidenschnur/data_ber_project_pandas)  
[Slides](https://slides.com/)
[Trello](https://trello.com/b/K5FdrW5H/flying-with-corona)  
