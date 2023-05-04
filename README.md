# Bayesian Blocks in R

This repository contains an R implementation of the Bayesian Blocks algorithm, a non-parametric method for creating adaptive histograms and revealing local data structure.

## Introduction

Bayesian Blocks is a non-parametric representation of data derived from a Bayesian statistical procedure, originally developed by D. Scargle for astronomical time series analysis. The algorithm is comparable to kernel density estimation (KDE) and efficiently discovers local structure in background data.

The main idea behind the Bayesian Blocks algorithm is segmenting the data interval into variable-sized blocks based on well-defined criteria. Each block contains consecutive data points that satisfy these criteria, resulting in an optimal partitioning of the data.

## Features

- Non-parametric method for adaptive histograms
- Efficient discovery of local structure in data
- Applicable to various types of data, including time series
- Optimal data partitioning using variable-sized blocks

## Example Datasets

This implementation has been tested on the following datasets:

- A dummy dataset to demonstrate the algorithm's functionality
- An energy spectrum dataset of an HPGe detector with Eu152

## Bibliography

[1] J. D. Scargle et al., Astrophys. J. 764 (2013) 167  
[2] B. Pollack et al., arXiv:1708.00810  
[3] J. D. Scargle et al., Astrophys. J. 504 (1998) 405  
[4] L. Pertoldi, The Bayesian Blocks algorithm from time series analysis to histogram representation, GERDA meeting presentation, 2018. Available [here](https://www.pd.infn.it/~agarfa/didattica/lpertoldi_bayesian-blocks.pdf)
