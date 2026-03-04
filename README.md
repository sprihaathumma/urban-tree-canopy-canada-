# 🌲 Urban Tree Canopy Change Detection — Toronto

Detecting urban tree canopy loss and gain using Sentinel-2 satellite imagery and Google Earth Engine.

## What this project does
- Loads Sentinel-2 SR imagery for Toronto (2019 vs 2023)
- Calculates NDVI to identify tree canopy coverage
- Detects change over time: gain (green) vs loss (red)
- Calculates canopy area statistics in km²

## Stack
Python · Google Earth Engine · geemap · geopandas · rasterio

## Data Sources
- Copernicus Sentinel-2 SR (via Google Earth Engine)
- Statistics Canada city boundaries

## How to run
```bash
conda activate geoenv
jupyter notebook notebooks/01_data_acquisition.ipynb
```
