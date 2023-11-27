# Globular Cluster Analysis - NGC 104 (47 Tuc) with Hubble Space Telescope Data

## Overview
This repository contains Python code for the analysis of a dense star cluster, specifically the globular cluster NGC 104 (commonly known as 47 Tuc), observed by the UVIS detector of the Wide Field Camera 3 (WFC3) on the Hubble Space Telescope. The project focuses on astrophysics and astronomy programming.

## Author
David Mathas - October 2023

## Dependencies
- `numpy`
- `pandas`
- `matplotlib`
- `astropy`

## Usage
The main script (`main_analysis.py`) performs the following tasks:
1. Opens the FITS file, extracts image data, and plots the cluster image with and without sky coordinates.
2. Examines a subset of the image and cleans the data.
3. Detects stars in the subset and plots their locations.
4. Performs star detection on the entire dataset.
5. Analyzes the center of the globular cluster and plots histograms with fitted functions.
6. Calculates and plots the stellar density profile of the cluster.
7. Fits the King model to the stellar density data and plots the results.

## How to Run
Make sure you have the required dependencies installed. Run the `main_analysis.py` script to execute the analysis.
