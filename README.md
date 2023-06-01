## Big Data Analysis with PySpark - WDI
---
> **Note** This repository has been archived.

> **Update:** only the way to install and import the PySpark package has changed. The rest of the code was written for PySpark 3.0.1 in 2021.

A Jupyter notebook with an example of big data analysis using the PySpark SQL module.
### Overview:
---
The objective is to learn tools of the PySpark SQL module for working with big data on an example of analysis of World Development Indicators. It used DataFrames and its methods, built-in functions, window functions, and converting SQL queries to DataFrame. Suitable for those who want to see how these tools work in practice.
### Setup:
---
The Jupyter notebook was created in Google Colaboratory, and the data was stored on Google Drive, so it's easier to open and run it there, but first replace or recreate all the data paths for loading and saving. 
### Versions of packages used:
---
python 3.10.11, pyspark 3.4.0
### Data: 
---
The dataset from [World Development Indicators, The World Bank](https://datacatalog.worldbank.org/dataset/world-development-indicators) licensed under a [Creative Commons Attribution 4.0 (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/) license: a zip archive with CSV files from the "Data & Resources" tab. Only the files "WDIData", "WDICountry", and "WDISeries" were used.
