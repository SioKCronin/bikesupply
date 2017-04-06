# Bike Supply

Bike Supply is an exploration of predictive models of bike sharing supply-demand dynamics, made possible by the generous data sharing of Bay Area Bike Share. 

## Goal

The goal of this project is to build model that predicts number of bikes that will enter each station in the network in the next two hours. 

## Business problem 

Bike sharing problems must reshuffle their supply to ensure bikes and docking stations are available throughout the day. 

In a perfect world, all bikes will arrive at the stations they are most needed in advance of their next renter needing them. However, the world is not yet perfect, and bike sharing companies must invest time and money on determining the best bike reshuffling protocols to ensure optimum supply at all stations. 

## Models

* Network Unaware: Predictions of supply dynamics based on historic data

* Network Aware: Predictions of supply dynamics based on historic data plus state data from that day. 

* Bayesian Model: Updated priors from today's bike rentals used to adjust posterior distributions of today's arrivals


