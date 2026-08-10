---
title: "Traffic Crash Prediction"
collection: publications
category: research-project
permalink: /projects/2025-Traffic-Crash-Prediction
excerpt: >
        University of Minnesota - Twin Cities, Fall 2025<br>
        Introduction to Data Mining (CSCI 5523) Final Project<br>
        Instructor: Vipin Kumar<br>
        Co-authors: Rehan Ahmad, Ian Corsiga, Jeffrey Qian, Clayton Sparrow
---

University of Minnesota - Twin Cities, Fall 2025

Introduction to Data Mining (CSCI 5523) Final Project

Instructor: Vipin Kumar

Co-authors: Rehan Ahmad, Ian Corsiga, Jeffrey Qian, Clayton Sparrow

## Project Summary

Tens of thousands of people die each year as a result of a traffic collision in the United States of America, with many more non-fatal, but still costly and life-altering traffic collisions occurring each year. We propose two theoretical approaches to predict locations of future traffic collisions, providing emergency response systems with areas of high alert and traffic engineers with areas that may need improvement. Using collision data from the Road Safety Information Center of Minnesota and weather data from the National Oceanic and Atmospheric Administration, we designed and constructed two prediction models to predict the most likely locations in the Twin Cities Metro Area to have a traffic collision on the following day. One model utilizes logistic regression, while the other is a simple artificial neural network (ANN). Both models were trained on crash and weather data from January 1st, 2016 to December 31st, 2023, then validated on the remaining data from January 1st, 2024 to September 30th, 2025. Several validation measures were taken, including ROC-AUC, log-loss, & the brier score. The ANN model showed better measures of reliability, including an ROC-AUC of 0.689 and high correlation between model probability and observed frequency, though the logistic regression also showed promising results. Future research should explore using additional data sources such as the Annual Average Daily Traffic and additional prediction models such as XGBoost.

## Personal Contributions
* Co-designed the predictive models and evaluation methodology
* Performed all of the preprocessing of data & exploratory analysis
* Assisted in the analysis of both models
* Wrote the Introduction, Dataset, Preprocessing, Exploratory Analysis, & Conclusions sections of the report.

## Skills Demonstrated:
* Data Mining
* Data Preprocessing
* Data Analysis
* Predictive Model Design
* Statistical Analysis of Prediction Models

## Technologies Used
* Python
* Jupyter Notebooks

## [Download Full Report](https://asbmeyers.github.io/files/Traffic_Crash_Prediction.pdf)

## [GitHub Repository](https://github.com/asbmeyers/CSCI-5523-Traffic-Crash-Prediction)

