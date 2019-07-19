# Developing optimal bicycle network growth strategies

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/nateraluis/bicycle-network-growth/master)

This repository contains the code to replicate the algorithms and measures in the paper [Natera, L.G., Battiston, F., Iñiguez, G., and Szell, M. *"Data-driven strategies for optimal bicycle network growth"*, 2019.](https://arxiv.org/abs/1907.07080)

## Guide
1. ```01_Multiplex.ipynb``` --> Takes the multilayer networks for the fifteen different cities and calculates their corresponding overlap census.
1. ```02_BicycleAlgorithms.ipynb``` --> Deploy the algorithms L2C, L2S, CC, and R2C to grow bicycle networks and calculates the bicycle-car directness.
1. ```03_Plots.ipynb``` --> Makes the plots with the measures of the algorithms.

The data we used for the analysis is available at [Harvard Dataverse](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/GSOPCK).
