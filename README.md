# GAO Rental Project Support Materials

This repository contains the main materials for my GAO Innovation Lab interview project, along with related graduate coursework that informed the modeling approach.

## Repository Contents

- `hoffman-australian-rental.ipynb`  
  Main project notebook. This contains the full analysis of the Australian Rental Market Data 2026 dataset, including data cleaning, exploratory analysis, staged model development, and interpretation of the final results.

- `hoffman-australian-rental.pptx`  
  Slide deck summarizing the project findings, modeling approach, and conclusions.

- `Regression.ipynb`  
  Related coursework notebook from **CS 441: Applied Machine Learning** at UIUC. Included as background context for the regression methods used in this project.

- `GLMnet.ipynb`  
  Related coursework notebook from **CS 441: Applied Machine Learning** at UIUC covering regularized regression concepts relevant to the modeling approach used here.

## Project Summary

The project analyzes weekly rental prices using the **Australian Rental Market Data 2026** dataset. The goal was to build an interpretable supervised learning model that explains how much rental price variation is driven by:

- property fundamentals
- geography
- amenities
- overall amenity richness

The analysis uses staged **Ridge** and **Lasso** regression models to compare how each feature group contributes to prediction quality and interpretation.

## Main Findings

- Property fundamentals explain some rent variation, but are limited on their own.
- Geography is the strongest driver of rental price in the dataset.
- Amenities add modest but consistent predictive value beyond fundamentals and geography.
- The final H5 model separates the general premium for feature-rich listings from the distinct associations of specific amenities.
- Ridge outperformed Lasso for final prediction because the signal was distributed across many correlated features.

## Coursework Context

The regularized regression framework used in this project was reinforced by recent coursework in **CS 441: Applied Machine Learning** at UIUC. Those materials are linked here as background context, but the rental project itself is an independent applied analysis that extends beyond the coursework by working with a new dataset, open-ended feature engineering, staged hypothesis testing, and model interpretation.

## Notes

This repository is intended to provide:
- the full project notebook
- the presentation deck
- supporting coursework context for the modeling methods used
