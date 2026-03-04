
# 🏠 Quantifying Location Premium in Airbnb Pricing

## Overview

This project analyzes Airbnb listings in San Francisco to evaluate:

> **Are prices driven primarily by intrinsic property features, or does neighborhood prestige create a measurable location premium?**

The analysis focuses on structured exploratory data analysis (EDA) and pricing decomposition to understand marketplace pricing dynamics.

---

## Tools

Python · Pandas · NumPy · Matplotlib · Seaborn · Scikit-learn

---

## Business Context

For marketplace platforms, pricing transparency and value alignment are critical.
This project investigates whether listing prices reflect:

* Property characteristics (size, amenities, room type)
* Host quality and review scores
* Geographic location and neighborhood clustering

The goal is to assess whether location contributes pricing power beyond observable property features.

---

## Dataset

Source: Inside Airbnb (San Francisco)

Features include:

* Property attributes (bedrooms, bathrooms, accommodates, amenities)
* Host characteristics
* Review scores
* Neighborhood identifiers
* Occupancy and estimated revenue metrics

---

## Methodology

**Data Preparation**

* Cleaned missing values
* Log-transformed price to address skewness
* Engineered `amenity_count`
* Removed extreme outliers

**Exploratory Analysis**

* Price distribution and skew analysis
* Neighborhood-level median pricing
* Room type segmentation
* Correlation analysis of structural drivers
* Geographic price clustering

---

## Key Findings

* Airbnb prices are strongly right-skewed; log transformation improves interpretability.
* Property size, room type, and amenities are primary price drivers.
* Premium neighborhoods form distinct high-price tiers.
* Geographic clustering suggests location-based pricing segmentation.
* Location appears to amplify pricing beyond structural property features, indicating a potential **location premium effect**.

---

## Skills Demonstrated

* Exploratory Data Analysis (EDA)
* Feature Engineering
* Data Cleaning & Transformation
* Log Transformation & Distribution Analysis
* Correlation & Grouped Aggregation
* Geospatial Visualization
* Marketplace & Pricing Analytics

---
