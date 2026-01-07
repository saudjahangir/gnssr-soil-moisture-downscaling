# GNSS-R Soil Moisture Downscaling using Multi-Sensor GeoAI

## Overview
This repository contains research code and reproducible workflows for downscaling coarse-resolution GNSS-R and SMAP soil moisture using multi-sensor geospatial data and machine learning.

The project treats GNSS Reflectometry (GNSS-R) as a large-scale, indirect geospatial sensing problem and applies GeoAI-based fusion to improve spatial resolution, robustness, and physical interpretability.

## Study Context
- Application focus: Agricultural regions (India)
- Temporal scope: Monsoon season (Kharif)
- Spatial challenge: Coarse GNSS-R footprints vs. field-scale variability

## Data Sources
- CYGNSS L3 Soil Moisture
- SMAP L3 Soil Moisture
- Sentinel-1 GRD (SAR backscatter, VV/VH)
- Sentinel-2 L2A (vegetation indices)
- SRTM DEM (terrain features)

> Due to data size and licensing constraints, raw datasets are not hosted in this repository.

## Methodology
1. Spatial and temporal harmonization of multi-source data
2. Feature extraction from SAR, optical, and terrain datasets
3. Machine learning–based downscaling (Random Forest / XGBoost)
4. Model evaluation using statistical metrics and cross-validation

## Tools & Technologies
- Python (NumPy, Pandas, Scikit-learn)
- Geospatial libraries (rasterio, geopandas)
- Google Earth Engine (cloud-based preprocessing)
- Jupyter Notebooks

## Repository Structure
## Status
Research prototype developed as part of postgraduate academic work.  
The workflow emphasizes scalability, reproducibility, and suitability for cloud-based GeoAI research.
