# FloodDynamics-XAI-Nigeria

## Overview
This repository hosts the research project **"Evaluating Pluvial and Fluvial Flood Dynamics in Data-Scarce Tropical Catchments: An Integrated Explainable AI (XAI) and Spaceborne SAR-Hydrodynamic Modeling Framework across North Central Nigeria"** by Joseph James Umar and Nelson Oyenbuchi Nwobi.

The project integrates:
- Sentinel-1 Synthetic Aperture Radar (SAR) imagery
- Geospatial predictors (hydro-geomorphic, atmospheric, land surface)
- Machine learning algorithms (Random Forest, XGBoost, LightGBM)
- Explainable AI (TreeSHAP)
- Population exposure mapping using WorldPop data

The workflow provides a reproducible framework for flood susceptibility modeling, mechanism disentanglement, and risk assessment in tropical, data-scarce environments.

---

## Repository Contents
- **FloodDynamics-XAI-Nigeria.ipynb** → The main Google Colab notebook containing the full workflow.  
- **FloodDynamics-XAI-Nigeria.ipynb** → Alternate copy of the notebook saved in the root folder for direct Colab use.  
- **/data** → CSV datasets and shapefiles (hosted in Google Drive, mounted in Colab).  
- **/scripts** → Supporting Python scripts for preprocessing and analysis.  
- **/results** → Outputs including hazard maps, model metrics, and exposure statistics.  

---

## How to Use
1. Clone or download this repository:
   ```bash
   git clone https://github.com/ArrenOnom/FloodDynamics-XAI-Nigeria.git
2. Or open the **FloodDynamics-XAI-Nigeria.ipynb** in colab and follow the instructions
