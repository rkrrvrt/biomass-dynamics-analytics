# Biomass Dynamics Analytics (Multi-Census & LiDAR Integration)

This repository contains an end-to-end R analytics data pipeline designed to clean, integrate, and model tropical forest field census data across two distinct temporal periods (Census 4 and Census 5) and pair them with aerial LiDAR remote sensing imagery to predict and analyze Above-Ground Biomass (AGB) dynamics.

## 🔒 Data Privacy & Disclaimer
* **Project Context:** This project was developed as part of an official internship program. 
* **Data Availability:** Due to strict data privacy agreements and institutional policies, the proprietary raw datasets (field census `.csv` files and aerial LiDAR `.tif` rasters) cannot be shared publicly. 
* **Repository Purpose:** This repository serves strictly as a portfolio to demonstrate technical capabilities, structured coding workflows, geospatial data pipelines, and quantitative analytical methodologies in R.

## 📁 Repository Structure & Workflow

The pipeline is structured chronologically into three key steps, with both source code (`.Rmd`) and rendered outputs (`.html`) provided:

* **`01_data_cleaning_eda`:** Handles data ingestion, rigorous taxonomic string correction, missing value treatments, and exploratory analysis (EDA) comparing tree structural metrics between Census 4 and Census 5.
* **`02_biomass_estimation`:** Employs the `BIOMASS` R package to cross-validate wood density datasets, model localized tree height curves, compute plot-level AGB, and evaluate changes across subplots.
* **`03_lidar_integration_modeling`:** Processes multi-temporal spatial LiDAR Canopy Height Models (CHM), clips study boundaries, extracts canopy metrics, and integrates remote sensing indicators with field-derived truths to yield predictive spatial insights.

## 🛠️ Key Technical Skills Demonstrated
* **Advanced Data Wrangling:** Pipeline engineering utilizing `dplyr`, `tidyr`, `purrr`, and `patchwork`.
* **Geospatial & Spatial Data Processing:** Managing complex raster/vector interactions via `sf`, `terra`, and `raster` libraries.
* **Statistical Modeling & Quantitative Inference:** Advanced application of specialized forestry biomass computing packages.
