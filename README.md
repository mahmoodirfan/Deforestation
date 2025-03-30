# Deforestation Analysis using Python

This repository is dedicated to analyzing deforestation and vegetation change using Python, satellite data (primarily Landsat), and Earth Engine. It includes scripts for generating high-quality maps, detecting forest loss using NDVI change detection, and producing visual outputs for reports and presentations.

## Project Overview

The scripts use Google Earth Engine (GEE) through the Python API (`ee`) and `geemap` to:

- Analyze temporal changes in vegetation
- Detect deforestation events based on NDVI drop
- Visualize land cover dynamics using remote sensing
- Generate publication-quality figures using `matplotlib`

**Key Features:**
- NDVI-based forest loss detection (threshold: NDVI decrease > 0.15)
- True-color map with forest loss overlay
- NDVI difference heatmap
- Scalebar, north arrow, legend, and stats panel
- Output: `Honduras_Forest_Loss_Presentation.png`

## 📦 Dependencies

To run the scripts, install the following packages:

pip install earthengine-api geemap matplotlib numpy matplotlib-scalebar

![Honduras_Forest_Loss_Presentation](https://github.com/user-attachments/assets/4efca7bb-dd57-41a9-ae11-d2d3baf6cf49)

