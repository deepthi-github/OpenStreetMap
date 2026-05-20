# Automated Extraction and Validation of Urban Road Networks from OpenStreetMap

## Overview

This dissertation project develops a geospatial data engineering workflow for extracting, validating, and enriching urban road networks from OpenStreetMap (OSM).

The project integrates OpenStreetMap road data with official UK Annual Average Daily Traffic (AADT) datasets to create a machine learning–ready traffic analysis dataset for Newcastle upon Tyne.

The workflow preserves both major and minor roads while validating topological consistency and spatial accuracy.

---

## Features

- OpenStreetMap road network extraction using OSMnx
- Geospatial preprocessing and CRS transformation
- Topological validation of urban road networks
- Integration of AADT traffic count datasets
- Spatial nearest-neighbour matching
- Feature engineering for machine learning
- Exploratory traffic analysis
- Road classification analysis
- Spatial quality assurance and validation
- Traffic trend visualisation

---

## Technologies Used

- Python
- Jupyter Notebook
- OSMnx
- GeoPandas
- NetworkX
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- GIS / Spatial Analysis

---

## Key Research Contributions

- Preserves minor roads often excluded in simplified transport datasets
- Integrates volunteered geographic information (OSM) with official traffic datasets
- Produces machine learning–ready geospatial datasets
- Supports urban mobility and pollution modelling workflows
- Provides scalable spatial validation methodology

---

## Results

- Extracted over 76,000 road segments and 40,000 network nodes
- Validated spatial matching between AADT count points and OSM roads
- Identified residential roads as the dominant urban road type
- Produced a harmonised traffic dataset suitable for predictive modelling

---

## Files

- `OSM_model.ipynb` → Main geospatial analysis notebook
- `Project_OSM_FINAL.pdf` → Final dissertation report
- `Automated Extraction and Validation of City Road Networks.pdf` → Research poster
- `Interim Report.pdf` → Interim project report

---

## Future Improvements

- Graph Neural Network (GNN) traffic prediction
- Spatial autoregressive modelling
- Pollution exposure modelling
- Urban accessibility analysis
- Integration of land-use and population density features
- Real-time traffic estimation workflows
