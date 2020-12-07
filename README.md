# Analysis of the Airbnb Berlin dataset

### Table of Contents

1. [About](#about)
2. [Objective](#objective)
3. [Installation](#start)
4. [Acknowledgements](#acknowledgements)

## About <a name="about"></a>

This repository contains the code of the Airbnb Berlin dataset data analysis. The dataset is made available directly on the Airbnb website: http://insideairbnb.com/get-the-data.html. 

The corresponding blog post can be found on medium: https://schrankf.medium.com/still-a-divided-city-4302d08c1d52

## Objective <a name="objective"></a>

The purpose of this analysis is to explore a dataset of Airbnb in Berlin with particular regard to the differences between the former East and West: 
1. _What are the key factors that influence the price?_
2. _Where are the most expensive neighbourhoods?_
3. _Where are the most popular neighbourhoods?_

![Alt text](./img/price_map_contrained.png?raw=true "Optional Title")

## Getting started <a name="start"></a>

**Installation**

The code should run with no issues using Python versions 3.\*. The easiest way to to work with the provided code is to use the `conda` environment manager and the provided environment file `environment.yml`. Simply create the a new environment by using:
```
conda env create --file environment.yml
```
Once you have created the environment, you need to activate it with 
```
conda activate airbnb
```

**File structure**

```
├── Airbnb_berlin_analysis.ipynb
├── LICENSE
├── README.md
├── enviroment.yml
├── data/
│   ├── berlin_wall.json
│   ├── berlin-wall.geojson
│   ├── listings.csv
│   ├── neighbourhoods.csv
│   ├── neighbourhoods.geojson
│   ├── reviews.csv
```

## Acknowledgements <a name="acknowledgements"></a>

My thanks go to Airbnb for sharing this data. The licensing of the data can be found under the link below:
http://insideairbnb.com/get-the-data.html







