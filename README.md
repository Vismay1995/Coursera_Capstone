# Coursera Capstone Project
The Word file "Report_Capstone_Neighborhoods" has all these in it but if you don't want to download that file than I have pasted everything below


Assignment of Week 4

Extensive Study on Neighborhoods of Toronto and New York City

Vismay Shah

May 29th, 2020


1.  Introduction

1.1. Background

Toronto is Canada’s business and financial capital. It is one of the fastest growing financial hub in North America and is in one of the top ten global financial centre. It is competitive in almost every other major business sector from technology and life sciences to green energy; from fashion and design to food and beverage; from film and television production to music and digital media[1]. Toronto’s rich industrial diversity has driven immense growth and diversity and attracted lot of immigrants. The number of immigrants have shown growth till date since 2000 and Toronto being the city of receiving enormous amount of immigrants compare to any other city of Canada[2]. Toronto is spread across 243.32 square miles (630.20 km2)  with the estimated population of 2,731,571 in 2018[5]. 

On the other hand, there is New York City which is described as the cultural, financial, and media capital of the world, significantly influencing commerce, entertainment, research, technology, education, politics, tourism, art, fashion, and sports[3]. It is commonly regarded as the finance capital of the world, has been ranked first in the World’s Financial Centers by the Global Financial Centers Index (GFCI). The city is a mix of various cultures from across the globe providing a diverse population and workforce[4]. With an estimated 2019 population of 8,336,817 distributed over about 302.6 square miles (784 km2), New York is also the most densely populated major city in the United States[3]. 

1.2. Objective

As both the cities have enormous opportunities of jobs and businesses to develop, it has always been the discussion amongst the people about the life of the people living there. The objective of this project is to comprehensively study the type of venues exist around each neighborhood of each borough of both the cities, and eventually compare how similar or different these cities and their neighborhoods are in terms of their surrounding venues using K means clustering machine learning algorithm.

1.3. Interest

This comprehensive study will definitely be of interest who want to start/expand their business in food industry or entertainment industry by getting to know the venues of the neighborhoods, who want to relocate from any other city to one of these cities or who actually lives in one of these cities and want to move to other one as they will get a good idea about the specific borough and neighborhood they are planning to move to,  who want to migrate internationally to one of these cities, whether it be for work or to study, will also get some prior information about specific location they are planning to migrate to.  

2. Data

The dataset of Toronto’s boroughs and neighborhoods was extracted from Wikipedia page only. The link of the page is https://en.wikipedia.org/wiki/List_of_postal_codes_of_Canada:_M. The Wikipedia page already has the data in table form so there was no need to reformat or modify the data except removing unnecessary rows and columns. Latitude and longitude of all those neighborhoods were provided by IBM in “.csv” format so again there was no need of data wrangling there.

The dataset of NYC’s boroughs and neighborhoods was imported in JSON format using this link https://cocl.us/new_york_dataset. From the dataset imported in the JSON format, useful features like name of the borough, name of the neighborhood, and their latitude and longitude were obtained and put them into pandas dataframe. As the dataset was already properly structured in the JSON format, there was again no necessity to modify it or clean it. 











3. References 
1) https://www.toronto.ca/business-economy/invest-in-toronto/strong-economy/
2) https://www.statista.com/statistics/444906/number-of-immigrants-in-canada/
3) https://en.wikipedia.org/wiki/New_York_City
4) https://www.investopedia.com/articles/investing/091114/worlds-top-financial-cities.asp
5) https://en.wikipedia.org/wiki/Toronto



