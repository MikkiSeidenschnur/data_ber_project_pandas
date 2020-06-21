<img src="https://www.bochum.de/C125830C0042AB74/CurrentBaseLink/W2BMMFEF129BOCMDE/$FILE/corona_3d_slider_ContentHalf.jpg" alt="Coronavirus :(" width="100"/>

# Flying with corona
*[Shelley Obery, Kyrian Bourgi, Mikki Seidenschnur]*

*[data analytics, Berlin & June 2020]*

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

Studies suggest that the aviation industry is responsible for 2.4% of the total greenhouse gas emission [Graver, Zhang, Rutherford](https://theicct.org/sites/default/files/publications/ICCT_CO2-commercl-aviation-2018_20190918.pdf). 

## Questions & Hypotheses
Following the extreme decline in air traffic, it seems interesting to make a correlation study, trying to prove/disporve the following hypothesis:

1. The aviation industry plays a major role in the total emission of greenhouse gasses on planet earth. This would suggest that the decrease in air traffic has caused a lower pollution level in general.

2. Covid-19 impacted cryptocurrencies positively 

3. Quarantine measure benefited new innovative businesses market players that have digitalized processes.



## Dataset
In order to confirm the trends we have been reasearching on, we have collected various datasets: 

1. Pollution Data / Flights scheduled data
We have first investigated into world pollution data that we have gathered from the world air quality index API, as well data about the scheduled flights for the months we have created visualisations to contrast the correlation between pollution and flights but have not been able to come to the conclusion that pollution level measured have changed.


2. Cryptocurrency Data
We have looked into cryptocurrency data more specifically Bitcoin as most of the other cryptocurrencies are correlated to it. We have found out that there has been an increase/recovery of BTC during the quarantine. however we cannot say if this is an increasing of value or if this is just the market recovering from the previous bearish trend.

3. Zoom Data
Finally as with the quaratine measures and the switch to home-office we wanted to be able to put into evidence the impact of this kind of measures on companies stocks. While most of the stock listed companies have seen their values decreasong, Zoom entered the market with the competitive advatange of offering both video conferences as well as "Teamviewer-like" features to control someones else distant computer. We can observe from the data collected from Yahoo Finance API and the graph we have created, that the price of Zoom reached three times the original value at the beginning of the quarantine, we believe the home-office trend played a big role in this huge rise of value.



## Database
Our data base is strucutred as follow : we have one table that contains pollution data that is related to the tables of flights tracked / cancelled, a second table for cryptocurrency data and finally Zoom stocks prices table.

## Workflow
1rst day : We have first done some research on potentially interesting research topic and questions we would like to answer. 
2nd day : We agreed on the topic and have split the datasets to be collected between us so we can have everything on time.
3rd day : We had all the data collected mostly through API scrapping, redefined our code that it is all in function as it was asked and finally created the data visualisations and finished the powerpoint presentation.

## Organization
We organized our work using Trello you can find more informations on the work process here : 

Our repository contains a folder called "data" which contains all the data we have collected and a second one called "modules" that includes all codes we have created to perform analysis. 

## Links
Organization / Workflow Trello Board: https://trello.com/b/K5FdrW5H/flying-with-corona

Datasets scrapped: https://github.com/MikkiSeidenschnur/data_ber_project_pandas/tree/master/data

Codes : https://github.com/MikkiSeidenschnur/data_ber_project_pandas/tree/master/data


[Repository](https://github.com/https://github.com/MikkiSeidenschnur/data_ber_project_pandas)  
[Slides](https://slides.com/)
[Trello](https://trello.com/b/K5FdrW5H/week-3-project)  
