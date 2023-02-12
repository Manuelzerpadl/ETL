# W3 Project - Extract, Transform, Load

![portada](https://github.com/Manuelzerpadl/ETL/blob/1fd43ca3223e9eb1d2028059f3f27a311425b9b7/data/image/what-is-etl-in-datawarehouse.png)

The purpose of this project was to apply the techniques learned to extract, transform and load data for further analysis. 

## Description
Find different sources of information using the extraction methods learned in class and create a database to make informative queries.


## Objective

- Determine if there is a relationship between the human development index in European countries with the suicide rate per 100,000 inhabitants in generation X and boomers.

- Find out which European country has the highest suicide rate per 100,000 inhabitants. 

- Which of the two generations studied has had more suicidal tendencies during the data time frame

## General analysis and cleaning

- First of all we have performed a data search to obtain csv files and also webscrapping. 

- Using the BeatifulSoup method we managed to scrape the human development index data of almost all European countries from 1990 to 2017.

- After having our data sources converted into DataFrames using the most common techniques such as .head, .info, .columns and .value_counts to obtain general information for each one.


## Analysis and visualization of the data
Year-to-year comparison of suicides by generations studied.
![Comparativageneration](https://github.com/Manuelzerpadl/ETL/blob/1fd43ca3223e9eb1d2028059f3f27a311425b9b7/data/image/Captura%20de%20pantalla%202023-02-12%20174806.png)

Ratio per 100,000 inhabitants the number of suicides, the highest was in Lithuania.
![map100khabratio](https://github.com/Manuelzerpadl/ETL/blob/1fd43ca3223e9eb1d2028059f3f27a311425b9b7/data/image/Captura%20de%20pantalla%202023-02-12%20190551.png)

Human development index
![idh](https://github.com/Manuelzerpadl/ETL/blob/1fd43ca3223e9eb1d2028059f3f27a311425b9b7/data/image/Captura%20de%20pantalla%202023-02-12%20190503.png)
