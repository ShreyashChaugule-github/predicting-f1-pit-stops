# Predicting F1 Pit Stops

A machine learning solution for the Kaggle Playground Series S6E5 competition focused on predicting whether an F1 driver will pit on the next lap.

## Overview

This project uses CatBoost with engineered race strategy features to predict the probability of a pit stop on the next lap.

## Features

* Driver
* Compound
* Race
* Lap Number
* Stint
* Tyre Life
* Position
* Lap Time
* Cumulative Degradation
* Race Progress
* Position Change

## Feature Engineering

* RaceProgress
* Position_Change
* Cumulative_Degradation
* TyreLife²
* TyreLife × Compound

## Model

* CatBoostClassifier
* 5-Fold Stratified Cross Validation
* AUC Evaluation Metric

## Results

| Model             | CV AUC |
| ----------------- | ------ |
| CatBoost Baseline | 0.9486 |

## Competition

Kaggle Playground Series S6E5 - Predicting F1 Pit Stops
