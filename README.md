# Analysis of the Airbnb Berlin dataset

A repository for the Airbnb Berlin project and post on Medium:
https://schrankf.medium.com/still-a-divided-city-4302d08c1d52

## About

This repository contains the code of the Airbnb Berlin dataset data analysis as a jupyter notebook.
The dataset is made available directly on the Airbnb website: http://insideairbnb.com/get-the-data.html.

## Objective

The purpose of this analysis is to explore a dataset of Airbnb in Berlin with particular regard to the differences between the former East and West: 
1. _What are the key factors that influence the price?_
2. _Where are the most expensive neighbourhoods?_
3. _Where are the most popular neighbourhoods?_

![Alt text](./img/price_map_contrained.png?raw=true "Optional Title")

## Requirements

To work with this repository, you need a Python interpreter and the Conda Python environment manager. To create the provided conda environment `environment.yml` run the following command in the terminal:
```
conda env create --file environment.yml
```
Once you have created the environment, you need to activate it with 
```
conda activate airbnb
```

The `Airbnb_berlin_analysis.ipynb` jupyter notebook contains all code, comprising data import, cleaning, and exploratory and descriptive data analysis.

## License

MIT
