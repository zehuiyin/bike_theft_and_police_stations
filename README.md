# How Close is Too Close? Exploring the Relationship Between Bike Theft and Police Facility Distance in Toronto
 
## Authors: 
- [Zehui Yin](https://zehuiyin.github.io/), [zehuiyin@gmail.com](mailto:zehuiyin@gmail.com)

## Supervision: 
- [Prof. Ethan Fosse](https://www.utsc.utoronto.ca/sociology/ethan-fosse)

## Project Overview:
This repository contains the source code for the R-based data analysis of the project **How Close is Too Close? Exploring the Relationship Between Bike Theft and Police Facility Distance in Toronto**. This project was completed for the course [SOCC70H3: Models of the Social World](https://utsc.calendar.utoronto.ca/course/socc70h3) at the University of Toronto Scarborough in Winter 2024.

## Abstract:
Bike thefts pose a significant deterrent to urban cycling. This research delves into the influence of police presence on bike thefts and the geographical scope of its deterrent effect. Leveraging bike theft records from 2014 to 2023 in Toronto, alongside the most recent Canadian census data, I employ two-way fixed-effect Zero-inflated Negative Binomial Regression models to scrutinize the impact of network walking distance to the nearest police facility on the number of bike thefts within each census tract. To ensure robustness, I present a variety of model specifications, including OLS multiple regressions, Poisson regressions, and standard Negative Binomial Regression. The findings indicate that a police facility within a 500-metre radius notably curtails bike thefts, with statistical significance at the 0.05 level. Yet, this deterrent effect wanes with increasing distance and becomes inconsequential beyond 500 metres. Furthermore, at distances exceeding 2 kilometres, the presence of police facilities does not influence the number of bike thefts. The study infers that police facilities exert a localized effect on bike theft prevention in urban areas. Consequently, merely increasing the number of police facilities city-wide is not an efficacious strategy for reducing bike theft. Policymakers are thus encouraged to consider alternative methods or strategies for enhancing crime deterrence.

## Research Questions:
This project addresses the following two research questions:
1. What causal influence does the presence of police facilities have on the frequency of bike thefts in Toronto?
2. Upon observing a deterrent effect, to what extent does the proximity of police facilities causally mitigate bike theft incidents in Toronto?

## Repository Contents:
To optimize storage, this repository hosts selected intermediate and final results data, excluding any extensive raw datasets. Access to the raw data can be obtained through the provided data source [link](./Data/data_source.xlsx).
