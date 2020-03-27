# Number of hospitals of the biggest cities around the world

## Introduction
Given the recent COVID-19 global pandemic, several major cities around the world will face infrastructure collapse related to health care, hospitals, and emergency services. At present, the Coronavirus has made thousands of victims around the globe. The World Health Organization reported the following statistics related to the pandemic:

* On average, 15% of the infected people need medical health care, with symptoms like fever, cough, chest discomfort, aches, and stuffy nose;
* On average, 5% of the infected people need intensive health care, including segregation and artificial breathing, presenting symptoms like shortness of breath, fever, coughs and chest discomfort;
* On average, between 2% and 5% of the infected people may occasionally die due to respiratory complications, infections, and pneumonia.
* People older than 65 years old, smokers, patients with respiratory problems, diabetes or immunosuppressed belong to the risky group and, have higher odds of serious complications and death.

## Business Problem
Based on those statistics, a city with 1 million citizens probably will have 150.000 infected people, who will need specialized health care and, in specific cases, intensive health care. Furthermore, between 20.000 and 50.000 infected people will die due to serious breathing complications.

Are those cities prepared to handle such pandemic? How many hospitals and intensive care services are in major cities around the world? What is the average patient per hospital rate? How do those cities compare to each other? How are the number of hospitals and the population size related?

## Data
For this project, I'll analyze the top 5 cities around the world, considering the population size. To perform this analysis, the following data will be necessary:

### Cities Population Size
The cities list will be defined based on the population size of the cities. This data will be used to calculate the infected group size, the patient per hospital rate and the correlation between different cities.

* https://en.wikipedia.org/wiki/List_of_largest_cities

### COVID-19 infection rate, number of deaths and symptoms
This data will be used to calculate infection and death rate, compared to the population size, among the different age tiers, symptoms, the number of hospitals and correlation between different cities.

* https://en.wikipedia.org/wiki/Coronavirus_disease_2019
* https://www.who.int/
* https://www.bing.com/covid

### Foursquare Location's API
The hospitals' locations of the biggest cities around the world will be extracted from the Foursquare API. Those coordinates will be used to plot heatmaps, choropleth maps, and other in-map visualization models.

* https://developer.foursquare.com/docs/api

### Additional Data
Additional data may be used to perform specific analysis or dataset processing.

## Jupyter Notebook
You can access the Jupyter Notebook here https://github.com/thiagobodruk/Coursera_Capstone/blob/master/hospital-cities.ipynb

## Report
You can access the report here https://github.com/thiagobodruk/Coursera_Capstone/blob/master/hospital-report.pdf

## Presentation
You can access the presentation slides here: https://github.com/thiagobodruk/Coursera_Capstone/blob/master/hospital-presentation.pdf
