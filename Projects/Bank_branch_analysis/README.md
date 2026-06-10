# Bank Branch Visits Analysis

## Overview

This project analyzes changes in consumer interest related to bank branch visits using search volume data. I collected keyword-level search volume data through an API and transformed it into a panel dataset to examine trends over time.

## Motivation
As digital banking services expand, many banks around the world have reduced the number of their physical branches.
This project explores whether consumer interest in bank branch visits has declined over time in South Korea as the number of physical bank branches has decreased, using search term statistics as a proxy for branch visit behavior.

## Data
The analysis uses keyword-level search term statistics collected through an API. 
Keywords were constructed as combinations of bank names and branch-related location terms. 
The dataset was then transformed into a panel structure with bank and time dimensions.  
Raw data are not included in this repository due to API usage restrictions.  


## Methods
- Downloaded a bank branch location dataset and used branch-level information to construct search keywords.
- Collected keyword-level search volume data using the Naver Search Trend API.
- Cleaned and reshaped the API responses into a bank-by-time panel dataset.
- Conducted exploratory analysis to examine changes in search interest related to bank branch visits over time.


## Tools
- Python
- [Naver Search Trend API](https://api.ncloud-docs.com/docs/en/ai-naver-searchtrend)   
- [Naver Datalab Search Trend](https://datalab.naver.com/)

## Results
