# Cryptocurrencies

## Table of Contents 
  - [Overview](#overview)
  - [Resources](#resources)
  - [Data](#data)
  - [Results](#results)
  
## Overview
This project uses unsupervised machine learning to group cryptocurrencies. The data is cleaned, principal component analysis is then used to reduce the dimensions. An elbow curve is created to get the best fit for the K-Means algorithm. Clusters are predicted and graphed. This is all completed within cryptoCompare.ipynb

## Resources
 - Visual Studio Code
 - python, pandas, plotly express, hvplot, sklearn

## Data
- crypto_data.csv, iris.csv, shopping_data.csv

## Results
Within the notebook various visualizations are created to show the clusters of cryptocurrencies. There is a 3D scatter plot, a 2D scatter plot, and a conventional table. These visualizations are created using plotly express and hvplot. The 3D scatter plot allows the viewer to see the relationship that principal component analysis created. The 2D scatter plot allows the viewer to see the relationship between total coin supply and total coins mined. The data presented in the scatter plots has been group via the K-Means algorithm. Overall this was an experiment in analyzing data using unsupervised machine learing to try and draw conclusions. 
