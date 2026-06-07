# disko-snow-ground-temperature-models
This repository contains the data processing, statistical analyses, and figures used in the manuscript:

> *Small-scale snow cover variability and its effect on ground surface temperatures in West Greenland* (under review in Arctic Science)

The study investigates how snow depth, snow density, vegetation, and topographic variables influence winter ground surface temperatures on Disko Island, West Greenland.

## Repository contents

- `sensor_data.csv` – processed temperature, topography, vegetation and snow measurements
- `Bayesian_models.ipynb` – analysis notebook containig model implementation
- `environment.yml`
  
## Data

The dataset includes measurements of:

- Snow depth
- Snow density
- Ground surface temperature
- Vegetation type
- Topographic variables (aspect, slope, elevation)

Data were collected on Disko Island, West Greenland, during the 2023–2024.

## Statistical models

The notebook implements multiple statistical models predicting ground surface temperature from:

- Snow depth
- Snow density
- Topographic variables
- Vegetation characteristics
- Soil moisture

Model descriptions, assumptions, and evaluation metrics are documented within the notebook.

## Reproducing the analysis

Run the notebook in the environment specified in `environment.yml` to reproduce the analysis.

## Citation

If you use this code or data, please cite:

Bauriedl, S. R. et al. (2026). *Small-scale snow cover variability and its effect on ground surface temperatures in West Greenland*.
