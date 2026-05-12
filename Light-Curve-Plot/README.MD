# Light Curve Visualization using Python

This project explores astronomical light curve data using Python and the Lightkurve library.

## Overview

A light curve is a graph of a star’s brightness (flux) over time. Periodic dips in brightness can occur when a planet passes in front of the star from our point of view, an event known as a transit.

By studying these variations, astronomers can estimate properties such as:
- orbital period
- relative planet size
- stellar variability

In this notebook, I experimented with downloading, plotting, and visualizing light curve data from the TESS mission using the Lightkurve package.

## Dataset

Target:
- TIC 100100827
(a planet which is also known as WASP-18)
- Sector 69

Source:
- TESS mission data accessed through the Lightkurve API
- SPOC pipeline products

## Tools Used

- Python
- Lightkurve
- Matplotlib
- Jupyter Notebook

## What the Code Does

- Searches for available TESS light curve observations
- Downloads selected sector data
- Plots flux vs time graphs
- Visualizes brightness variation patterns

## Sample Visualization



## What I Learned

- Basic handling of astronomical observation data
- Accessing TESS datasets programmatically
- Plotting and interpreting light curves
- Working with scientific Python libraries

## Future Improvements

- Transit detection
- Noise reduction and preprocessing
- Period analysis
- Multi-sector comparison
- Exoplanet candidate identification

## Note

This is a beginner-level exploration project created while learning astronomical data analysis and scientific computing techniques.
