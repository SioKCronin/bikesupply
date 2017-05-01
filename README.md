# Bike Supply

Bike Supply predicts bike availability based on previous activity in bike sharing networks. 

## Overview

The goal of this project is to build a model that can predict the number of bikes that will enter each station in a bike sharing network within the next thirty minutes. 

Bike sharing programs reshuffle their supply to ensure bikes and docks are available throughout the day. This is typically carried out by a street team (and a mighty van). If it were possible to accurately predict where bikes would be moving in the near future, the bike redistribution path could be optimized. 

## Design 

The modeling process followed the following development:

* EDA 
* Historical averages as point estimates
* Traditional GLM
* Conditional probability binning
* Bayes updating

## Validation

These models are being developed and validated with open data from [Bay Area Bike Share](http://www.bayareabikeshare.com/open-data). My hope is to, in time, tune this model to data from other [cities](https://github.com/BetaNYC/Bike-Share-Data-Best-Practices/wiki/Bike-Share-Data-Systems).
