# Comparison of Empirical Probability Distributions

_Topics:_ Comparison of empirical probability distributions. Integral probability metrics (e.g. Kantorovich metric). f-divergences (e.g. Kullback-Leibler). Application to the Choquet integral.

## Abstract

This repository completes the report of my final-year project at [Ecole des Mines de Nancy](https://mines-nancy.univ-lorraine.fr/formation/ingenieur-civil-mines-icm/).
The end goal of this project is to **compare two empirical probability distributions** from two different methods for computing the Choquet integral.

The first chapter is about the **Choquet integral**, a non-linear aggregation operator. We provide a lot of explanations and examples so that someone new to the Choquet integral can get a good understanding of it. %Indeed, understanding deeply how the Choquet integral works can be very useful in order to find the right metric for comparison.

The second chapter is about **integral probability metrics** (IPMs), a popular estimation of distance measures on probabilities.
In particular, we deal with the **Kantorovich metric** and the Dudley metric.
We also study the empirical estimation of the Kantorovich metric and implement it with Python.

The third chapter is about **f-divergences**. f-divergences are another method for computing the distance between two probability distributions.
In particular, we deal with the **Kullback-Leibler divergence**, the **Hellinger distance** and the **Variational distance**.
We also study the empirical estimation of these f-divergences and implement them with Python.

The fourth (and last) chapter applies the previous results on IPMs and f-divergences to the data obtained from the two methods for computing the Choquet integral.

## How to use this repository

We recommend reading the report before reading the notebooks, as most explanations are not duplicated in the notebooks. All notebooks are in Python 3. According to my report, the files should be read in this order:
1. `ipm-prerequisite.ipynb`: an introductory notebook that help to understand `ipm.ipynb` better
2. `ipm.ipynb`: core programs that generated the simulations in the chapter II about the Kantorovich metric (an IPM)
3. `f-divergences.ipynb`: core programs that generated the simulations in the chapter III about the f-divergences

Further information is given in the beginning of the notebooks themselves.
