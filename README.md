# Master-thesis
![GitHub last commit](https://img.shields.io/github/last-commit/aandyrea/master-thesis?color=%23ff69b4)
[![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/)
![GitHub commit activity](https://img.shields.io/github/commit-activity/y/aandyrea/master-thesis)
## Overview
This file explains the steps to reproduce the research carried out for my Master Thesis, titled "Refugees Welcome? A comparative sentiment analysis of tweets in Germany surrounding inflows of Syrians and Ukrainians". 

The project aims to collect and analyze immigration-related tweets published in Germany in English and German during two time frames:
1. The Syrian refugee inflow
2. The Ukrainian refugee inflow

All steps are documented in the Notebooks:
* 01_Data-Collection_limited_Syrian.ipynb
* 01_Data-Collection_limited_Ukrainian.ipynb
* 02_Pre-processing_limited_merged.ipynb
* 03_Sentiment-Analysis_limited_merged.ipynb
* 04_Data-Preparation_limited_merged.ipynb
* 05_Exploration-and-Visualization_limited_merged.ipynb
* 06_Regression_limited_merged.ipynb

## Installation
Please refer to requirements.txt

## Technologies
This project was created with: 
* Python 3.9.13

Notebook 03_Sentiment-Analysis_merged.ipynb was carried out in:
* Google Colab

All other Notebooks were carried out in:
* JupyterLab 3.4.8

## Notebooks

### 01_Data-Collection_limited_Syrian
The collection of tweets during the first time frame--the Syrian refugee inflow--is documented in this notebook. Both English- and German-language tweets are obtained.

### 01_Data-Collection_limited_Ukrainian
The collection of tweets during the second time frame--the Ukrainian refugee inflow--is documented in this notebook. Both English- and German-language tweets are obtained.

### 02_Pre-processing_limited_merged
In this notebook, all collected tweets are pre-processed for sentiment analysis.

### 03_Sentiment-Analysis_limited_merged
Sentiment analysis is carried out in this notebook. 
**NOTE**: This notebook was produced and run in Google Colab. Therefore, it is recommended you run it in Colab rather than Jupyter. 

### 04_Data-Preparation_limited_merged
The data is prepared for exploration and eventual regression in this notebook.

### 05_Exploration-and-Visualization_limited_merged
Here, the data is explored and visualized.

### 06_Regression_limited_merged
The final step of the study is carried out in this notebook. A logistic regression is conducted to predict sentiment based on inflow (Syrian or Ukrainian).
**NOTE**: This notebook is not yet currently available. It will be uploaded after the regression analysis is complete (ETA: end of March).
