![](https://github.com/RahalK/sql_weather_trends_france/assets/149255583/d0834a84-be73-4b5a-9ac5-afd01a036d65)

## Table of content
* [Overview](#Overview)
* [Objective](#Objective)
* [Data](#Data)
* [Approach](#Approach)
* [Skills](#Skills)
* [Technical tools](#Technical-tools)

## Overview
This SQL project focuses on analyzing weather data collected from three French cities (Paris, Lyon and Nice), combining information from from two tables, such as latitude, longitude, datetime, temperature, wind speed, and more. 
The project includes various SQL queries and analyses to extract insights from the tables. 

## Objective
The goal here is to gain insights into weather patterns, identify trends, and answer specific questions related to the provided tables.
More specifically, the analysis is intended to answer several questions, including – but not limited to:
* How does temperature vary across different locations and time periods?
* Are there any patterns in wind speed and direction?
* Can we identify days with extreme weather conditions?
* How does UV index change with the time of day?

## Data
The data comes from a weather API provided by [Meteomatics](https://www.meteomatics.com/), a leading provider of meteorological data. Two tables are used for this project: 'temperature_france' and 'weather_france'.
The 'temperature_france' tables contains 1299 rows and 6 columns, whereas 'weather_france' contains 1299 rows and 10 columns.

## Approach
The project is organized into the following sections:
* Dataset information: a brief overview of the dataset, including the columns and data types
* Data exploration: exploratory queries and analyses to understand the structure of the data
* Further analysis and insights: detailed SQL queries and analyses performed to derive insights from the dataset
* Advanced SQL queries: complex queries using advanced SQL features such as window functions, CTEs, subqueries, and aggregations

## Skills
* Data analysis
* Data manipulation
* Data type conversion
* Joins
* Filters
* Aggregate functions
* Window functions
* Common table expressions (CTE)
* Subqueries
* CASE statements
* Views

## Technical tools
* Microsoft SQL Server: used for analysing and manipulating the data
* Microsoft SQL Server Management Studio: used for storing the datasets, writing and executing SQL queries
* Meteomatics API for weather data: the data source 
