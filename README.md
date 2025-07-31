# NYC 311 Data Pipeline

A Python-based data analysis pipeline for exploring, modeling, and visualizing NYC 311 complaints at the ZIP code level.

## Overview

This project analyzes **NYC 311 service request data** to uncover patterns and trends in public complaints at the ZIP code level. Designed for **city planners**, **NYC residents**, **government agencies**, and **data scientists**, it helps identify which neighborhoods are more prone to specific types of complaints. By focusing on **ZIP codes** instead of broader boroughs, the project highlights the unique challenges faced by smaller communities and supports more localized, data-driven decision-making.

**Key features include:**

- Categorizing ZIP codes by complaint volume (**low, medium, high**) using **dynamic thresholds** and **IQR-based outlier detection**
- Adjusting complaint rates by ZIP code **population** to better reflect **per-capita trends**
- Visualizing complaint patterns by **month** and **day of the week** to anticipate service demands
- Modeling the expected frequency of daily complaints across the city using **probability distributions** and **prediction models** to assess how interventions may affect long-term trends

Built with tools like `pandas`, `seaborn`, `matplotlib`, `numpy`, `scipy`, and `plotly`, this project brings together both **statistical analysis** and **interactive visualizations** in a clean and reproducible **Jupyter Notebook** environment. Whether you're exploring **NYC's civic data** or building **predictive frameworks for urban policy**, this project offers a detailed, scalable approach to understanding **service complaint dynamics**.

## Folder Structure

- `notebooks/` — Jupyter notebooks for data ingestion and exploratory data analysis (EDA)
- `data/raw/` — Raw data files as downloaded
- `data/cleaned/` — Cleaned and processed data files
- `requirements.txt` — Python libraries needed for this project

## Notebooks

1. `01_data_ingestion.ipynb` — Load and save raw data from the source  
2. `02_eda.ipynb` — Explore and visualize the data to understand patterns and quality  

## How to Run

1. Install dependencies:

   ```bash
   pip install -r requirements.txt


   

