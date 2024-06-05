# Compound Floods
This public repository contains all code for the project entitled: "A Nonstationary Stochastic Simulator for Clustered Regional Hydroclimatic Extremes to Characterize Compound Flood Risk."

Below we outline the files included in the repository and their contents. This repository is currently under revision and being updated and refined for easy user access and implementation.

## Main.ipynb
This Jupyter notebook is the main script to run the compound flood simulator. The notebook is broken into sections. The section entitled "Input Parameters" allows users to specify all necessary model inputs.

## Wavelet.py
This python file contains all functions for wavelet transformation and signal processing steps.

## Trend.py
This python file contains all functions for trend extraction.

## Forecast.py
This python file contains all functions for signal forecasting.

## NS_Cluster.py
This python file contains all functions for modified Neyman-Scott Clustering.

## Data_Load.ipynb
This Jupyter notebook allows for rapid pre-processing of hydrologic timeseries to format data properly for input. Script assumes data is directly scraped from USGS and requires inputs based upon the data source.
