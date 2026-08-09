
# Behavioural Classification and Grazing Analysis

## Overview

This project analyses GPS collar and accelerometer data from Highland cattle monitored on Gloucestershire Wildlife Trust reserves between 2021 and 2024. The workflow classifies cattle behaviour using Hidden Markov Models and produces habitat preference maps to support conservation grazing management.

## Objectives

- Quantify seasonal variation in cattle activity.
- Classify active and resting behavioural states using Hidden Markov Models.
- Map seasonal and annual spatial distribution of behavioural states.
- Assess habitat use across the reserve.

## Methods

- Python (pandas, NumPy, GeoPandas, Folium)
- R (momentuHMM, sf, dplyer)
- Survey123 Behavioural Monitoring
- Hidden Markov Model
- GIS spatial analysis
- Confusion matrix validation
- Interactive mapping with Folium
- Quarto reproducible reporting

## Results

- Hidden Markov Model - confusion matrix
- Behavioural classification accuracy: 90.4%
- Active-state precision: 91.2%
- Active-state recall: 89.2%
- Interactive map aggregated over study period
- Habitat use map

<img width="585" height="730" alt="GrazingPreference" src="https://github.com/user-attachments/assets/e3ff175a-2c58-4257-a268-d19eb997c0b9" />

## Future Work

- Effect of behavioural state use on habitat specific vegetation indicators
- Influence of weather on GPS location and behaviour

## Report

Access report here:
[NoFenceProject.html](https://github.com/user-attachments/files/30875489/NoFenceProject.html)
