# Mind the Gap: Predicting TTC Subway Delays with a Machine Learning Approach

Authors: Petru Codrescu, Andre Sanchez-Plehn, Sean Chua, and Julia Tan

## Overview

This submission presents a machine learning analysis for forecasting TTC subway delays. By leveraging TTC subway data from 2023 and 2024, a neural network was created to identify stations with the highest predicted delays and provide insights for operational optimizations. The analysis is conducted in R and Python, utilizing ML techniques to estimate station-specific delay patterns. The final report found in our notebook (`MindTheGap.ipynb`) details the dataset, methodology, and key findings that may assist transit authorities in optimizing scheduling and improving overall efficiency.

## Submission Files

The submission contains the following:

-   `ttc-delay-cleaning.rmd` contains the R code used to download and clean data.
-   `MindTheGap.ipynb` contains all data (simulation, raw, analysis, as well as external data) relevant to the research.

## Statement on LLM usage

Aspects of the code were developed with the assistance of ChatGPT and GitHub Copilot. The **cleaning** and **preprocessing** of data as well as parts of the **neural network** were generated using these chatbots.

## Installation Instructions

To replicate the analysis and run the code in this repository, you'll need to install several R and Python packages. You can install R packages directly from CRAN using the following command in your R console:

```R
install.packages(c("opendatatoronto", "dplyr", "stringr"))
```
