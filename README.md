# Compound Floods
This public repository contains all code for the project entitled: "A Nonstationary Stochastic Simulator for Clustered Regional Hydroclimatic Extremes to Characterize Compound Flood Risk." All code to replicate the work done in the paper along with the supplementery materials is archived here. Below I outline the files included in the repository and their contents. 

## Abstract
Traditional approaches to flood risk management assume flood events follow an independent, identically distributed (i.i.d.) random process from which static risk measures are computed. Modern risk accounting strategies also consider nonstationarity or long-term trends in the mean and moments of the associated flood probability distributions. However, few approaches consider how extreme hydroclimatic events tend to cluster in both space and time, compounding damage risks. Here we introduce a compound flood risk simulator which models and conditionally forecasts future variability in regional flooding events that cluster in time, given trends and oscillations in a variable climate signal. A modular, novel integration of wavelet signal processing, k-nearest neighbor (KNN) bootstrapping, multivariate copulas, modified Neyman-Scott (NS) event clustering, and nonstationary time series forecasting provides users the ability to model interannual and sub-annual clustering of flood risk. Our semi-parametric flood generator specifically targets the clustered temporal dynamics of jointly modeled flood intensity, duration, and frequency over a finite future period of a decade or more, thereby providing a foundation for adaptation approaches that integrate temporally clustered flood risk into planning, response and recovery.

NOTE: This repository and associated code (including the README) is currently under maintenance and in process of being refined to enhance user experience for easy implementation. Please contact directly about current code files. Once research is formally published, all code should be up to date and this message will be removed.

# Repository Contents

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

# Contact Me!
If you have general questions about the code, model, or data please feel free to reach out and I am always happy to try to do my best to help out. If you're interested in using similar method or working on a new project, I am always looking to collaborate and am happy to contribute more broadly! Email is always in flux - but try me at adam.nayak@columbia.edu, adam.nayak@alumni.stanford.edu, adamnayak1@gmail.com, or feel free to ping me on LinkedIn.
