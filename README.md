# Behavioural Classification and Grazing Analysis

## Overview

This project analyses GPS collar and accelerometer data from Highland cattle monitored on Gloucestershire Wildlife Trust reserves between 2021 and 2024. The workflow evaluates seasonal variation in accelerometer activity time-series, classifies cattle behaviour using Hidden Markov Models and produces habitat preference maps to support conservation grazing management.

## Objectives

- Quantify seasonal variation in cattle activity.
- Classify active and resting behavioural states using Hidden Markov Models.
- Map seasonal and annual spatial distribution of behavioural states.
- Assess habitat use across the reserve.

## Workflow

<img width="1202" height="654" alt="NoFenceWorkflow" src="https://github.com/user-attachments/assets/37ea2344-69dc-4967-86e1-7778e894081e" />



## Methods

This project combines:
- Data cleaning and preprocessing in Python
- Analysis of seasonal variation in accelerometer activity timeseries
- Hidden Markov Model behavioural classification
- Validation using independent behavioural observations
- Seasonal habitat preference analysis
- GIS mapping and interactive visualisation
- Quarto reproducible reporting 


## Results

- Seasonal timeseries graph comparison

  <img width="1000" height="600" alt="Overall Activity Profile" src="https://github.com/user-attachments/assets/7403904a-267b-4492-8961-c78cf9fe0575" />

- Hidden Markov Model - confusion matrix
- Behavioural classification accuracy: 90.4%
- Active-state precision: 91.2%
- Active-state recall: 89.2%
- Interactive map aggregated over study period
- Habitat use map

<img width="585" height="730" alt="GrazingPreference" src="https://github.com/user-attachments/assets/e3ff175a-2c58-4257-a268-d19eb997c0b9" />

## Skills Demonstrated

- Python (pandas, NumPy, GeoPandas, Folium)
- R (momentuHMM, sf, dplyer)
- Survey123 Behavioural Monitoring
- Hidden Markov Model 
- GIS spatial analysis
- Confusion matrix validation
- Interactive mapping with Folium
- Quarto reproducible reporting

## Future Work

- Effect of behavioural state use on habitat specific vegetation indicators
- Influence of weather on GPS location and behaviour

## Report

Access report here:
[NoFenceProject.html](https://github.com/user-attachments/files/30875601/NoFenceProject.html)

