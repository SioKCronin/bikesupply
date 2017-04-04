# Bike Supply

Bike Supply is a PyMC3-driven Bayesian predictive model of an urban bike share company's supply-demand dynamics. 

## Goal

The model was built using public data supplied by Bay Area Bike Share, the hope of answering the question - is it possible to build a model that predicts the number of bikes that will enter each station in the network in the next few hours? 

## Business problem 

Transporation sharing services have unique supply chain dynamics. While Bay Area Bike Share is not a two-sided marketplace in the classic sense, it is true that the bike you rent from station A was either 1) there since the start of the company (poor bike), 2) desposited there by another rider, or 3) desposited there by the company in an act of supply reshuffling. 

In a perfect world, all bikes will arrive at the stations they are most needed in advance of their next renter needing them. However, the world is not yet perfect, and bike sharing companies must invest time and money on determining the best bike reshuffling protocols to ensure optimum supply at all stations. 


