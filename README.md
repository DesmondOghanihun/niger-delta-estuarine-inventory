# Niger Delta Estuarine Inventory

Python workflow for a GIS inventory of estuarine and coastal creek systems in the Niger Delta, Nigeria.

## Overview

This repository contains the Python code used to generate a GIS inventory of 23 estuarine and coastal creek features across Delta, Bayelsa, and Rivers states, digitised from Google Earth Engine satellite imagery (Landsat 8 OLI and Sentinel-2 MSI).

The Niger Delta waterway network is highly complex and dynamic. This inventory captures the major features identifiable from satellite imagery; smaller creeks and seasonally inundated channels require further field verification.

## Contents

- `Code_S1_GIS_Inventory.py` — main script for KML processing, spatial analysis, and cartographic production
- `Code_S1_Figure2_Distribution.py` — script for the feature distribution bar chart
- `Table_S1_Feature_Metadata.csv` — metadata for all 23 features
- `README.md` — this file

## Requirements

- Python 3.10+
- geopandas, matplotlib, contextily, fiona, shapely, pandas, numpy, pysal

Install with:

```bash
pip install geopandas matplotlib contextily fiona shapely pandas numpy pysal