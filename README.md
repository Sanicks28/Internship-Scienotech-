
# Dual VEML6040-Based Currency Detection System

## Overview

This project implements a currency detection and classification system using two VEML6040 color sensors. The system captures reflective and color properties of banknotes under different lighting conditions to identify currency denominations and variants.

## Dataset

The dataset contains raw and derived features from two sensors, including RGBW values, ambient light, color temperature, XYZ and HSV color spaces, and normalized features.
Target column: `Class` (currency denomination and variant).

## Objective

To classify currency notes and distinguish between different denominations and versions (e.g., old vs new) under varying lighting conditions.

## Workflow

* Data collection using dual sensors
* Data preprocessing and cleaning
* Exploratory data analysis
* Feature engineering
* Preparation for classification models

## Technologies

Python, Pandas, NumPy, Matplotlib, Seaborn

## Future Work
* Deploy on embedded systems
* Improve performance in real-world environments


