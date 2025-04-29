# Sci4GA Energy and Emissions Analysis

This repository contains notebooks used to support Sci4GA’s analysis of how energy infrastructure and emissions impact Georgia communities.

The project focuses on:
- Mapping power plants to ZIP codes,
- Analyzing trends in air pollution over time,
- Studying the relationship between energy production, environmental factors, and local housing markets,
- Cleaning and preparing related datasets for deeper analysis.

## Current Notebooks

### `CoordinatesToZIP.ipynb`
**What it does**:  
Converts latitude and longitude coordinates of power plants into ZIP codes using geocoding.

**Why it was used**:  
To link each power plant to local housing, demographic, and health data by ZIP code.

---

### `Graph Generation Trends and Technology ZIP.ipynb`
**What it does**:  
Creates graphs showing:
- Housing price differences near different energy technologies,
- NOₓ emissions trends by source (vehicles, industry, power plants) from 2002–2019.

**Why it was used**:  
To visualize how energy production and emissions affect Georgia’s environment and economy.

---

### `Preliminary Code for Data Collection Cleaning and Exploration.ipynb`
**What it does**:  
Performs initial data exploration, cleaning, and organization of datasets from multiple sources.

**Why it was used**:  
To understand available data and prepare it for deeper analysis.

---

### `clean PLACES data.ipynb`
**What it does**:  
Cleans public health data from the CDC’s PLACES dataset.

**Why it was used**:  
To make health indicators usable for mapping and linking to energy infrastructure and demographics.

---

### `cleaning Generation data.ipynb`
**What it does**:  
Cleans electricity generation data from the U.S. EIA (Energy Information Administration).

**Why it was used**:  
To connect generation types and amounts with ZIP codes and other regional factors.

---

## How to Run the Notebooks

1. Install the required Python packages:
```bash
pip install pandas matplotlib numpy openpyxl geopy
