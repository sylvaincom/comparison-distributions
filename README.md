# Comparison of Empirical Probability Distributions

## Quick preview

- _Author_: Sylvain Combettes
- _Dates_: Oct. 2019 - Feb. 2020 (5 months)
- _Context_: For my final-year project at Mines Nancy (one day per week), I did research for the [CNRS](http://www.cnrs.fr/en), the largest governmental research organisation in France.
- _Topic_: Comparison of empirical probability distributions. Application to the Choquet integral with stochastic inputs.
- _Methods_: Integral probability metrics (e.g. Kantorovich metric), f-divergences (e.g. Kullback-Leibler).
- _Programming_: Python.
- _Result_: We empirically show that a new method for simulating the Choquet integral is "correct".
- _Links:_  [[report](https://sylvaincom.github.io/docs/comparison_distributions_report.pdf)] [[slides](https://sylvaincom.github.io/docs/comparison_distributions_slides.pdf)]

## Abstract

This repository completes the report of my final-year project at [Ecole des Mines de Nancy](https://mines-nancy.univ-lorraine.fr/formation/ingenieur-civil-mines-icm/).
The end goal of this project is to **compare two empirical probability distributions** from two different methods for computing the Choquet integral.

The first chapter is about the **Choquet integral**, a non-linear aggregation operator. We provide a lot of explanations and examples so that someone new to the Choquet integral can get a good understanding of it.

The second chapter is about **integral probability metrics** (IPMs), a popular estimation of distance measures on probabilities.
In particular, we deal with the **Kantorovich metric** and the Dudley metric.
We also study the empirical estimation of the Kantorovich metric and implement it with Python.

The third chapter is about **f-divergences**. f-divergences are another method for computing the distance between two probability distributions.
In particular, we deal with the **Kullback-Leibler divergence**, the **Hellinger distance** and the **Variational distance**.
We also study the empirical estimation of these f-divergences and implement them with Python.

The fourth (and last) chapter applies the previous results on IPMs and f-divergences to the data obtained from the two methods for computing the Choquet integral.

## How to use this repository

We recommend reading the report before reading the notebooks, as most explanations are not duplicated in the notebooks. All notebooks are in Python 3. According to my report, the files should be read in this order:
1. `ipm-prerequisite.ipynb`: an introductory notebook that helps to understand `ipm.ipynb` better
1. `ipm.ipynb`: core programs that generated the simulations in chapter II about the Kantorovich metric (an IPM) and also a part of chapter IV
1. `f-divergences.ipynb`: core programs that generated the simulations in chapter III about the f-divergences and also a part of chapter IV

More information is given in the beginning of the notebooks themselves.