# Evology 

![Tests](https://github.com/aymericvie/evology/actions/workflows/runs.yml/badge.svg?branch=master)

## Presentation

Evology is a large-scale multi-agent simulation of the US stock market, focused on modelling mutual funds. Each simulated fund and stock respectively correspond to real funds and stocks, initialised with historical holdings and fundamentals data. In this model, mutual funds follow reconstructed trading strategies. The resulting stock demand and supply determine prices through market clearing. 

### Evology in numbers
* Quarterly simulation between 2012 and 2023 for 44 quarters
* 1,741 unique stocks, primarily in S&P 500 and Russell 2000 indexes universes
* 9,094 unique mutual funds, initialised with historical portfolio holdings and portfolio-based trading strategies
* Simulated holdings cover 26% of the total stock market value in our stock universe.

## Applications 
Evology in its current version is the first step towards a complete multi-agent 1:1 simulation of the US stock market. The first application is forecasting several market variables (e.g. stock returns, volatility, funds' individual trades, performance of funds or aggregate investment styles) conditional on fundamentals and on sufficient simulation coverage. Evology also allows testing various counterfactual scenarios: its emergent approach makes returns and trading activity endogenous and dynamic. Finally, Evology allows testing trading strategies under market impact and strategic interactions.

## Software and data
Evology is primarily developed in Python and Cython for speed purposes, with an object-oriented design. Data used for modelling include CRSP, Compustat, SEC-EDGAR and other leading financial services providers.

## Contact, credits and funding

Code developed by Aymeric Vié at the University of Oxford - Mathematical Institute. You can contact me at vie[at]maths.ox.ac.uk. 
This research has been supported by the EPSRC Centre for Doctoral Training in Mathematics of Random Systems: Analysis, Modelling and Simulation (EP/S023925/1)
