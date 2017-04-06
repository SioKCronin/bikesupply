# Bike Supply

Bike Supply is a Bayesian predictive model of bike sharing supply-demand dynamics.

## Goal

The goal of this project is to build model that predicts number of bikes that will enter each station in the network in the next two hours. 

## Business problem 

Bike sharing problems must reshuffle their supply to ensure bikes and docking stations are available throughout the day. 

In a perfect world, all bikes will arrive at the stations they are most needed in advance of their next renter needing them. However, the world is not yet perfect, and bike sharing companies must invest time and money on determining the best bike reshuffling protocols to ensure optimum supply at all stations. 

## Models

* Network Unaware: Predictions of supply dynamics based on historic data

* Network Aware: Predictions of supply dynamics based on historic data plus state data from that day. 

* Bayesian Model: Updated priors from today's bike rentals used to adjust posterior distributions of today's arrivals

## Data

This model is being developed and validated with open data from [Bay Area Bike Share](http://www.bayareabikeshare.com/open-data). My hope is to tune this model to other [cities](https://github.com/BetaNYC/Bike-Share-Data-Best-Practices/wiki/Bike-Share-Data-Systems). But first things first, let's get this thing working!



