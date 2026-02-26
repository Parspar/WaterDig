# WaterDig

## Name
Parsa Parvizi

## Contact Information
Email: parsa.parvizi@oulu.fi  
GitHub: https://github.com/Parspar  

## Organizational Affiliation
University of Oulu  
Water, Energy and Environmental Engineering   Unit (WE3)

## Professional Links
- GitHub: https://github.com/Parspar
- LinkedIn: Parsa Parvizi | LinkedIn
- Google Scholar: ‪Parsa Parvizi‬ - ‪Google Scholar‬

# Project Overview

## Problem Statement
Water systems in northern and boreal environments are highly dynamic and sensitive to climate change. Understanding soil moisture dynamics is essential for sustainable water resource management, carbon cycling studies, and ecosystem protection.
## Challenge Statement
Soil moisture dynamics are difficult to measure directly due to:
- High spatial and temporal variability  
- Seasonal snow influence and snow melt regime
- Limited observation points and hard work in field
- Complex subsurface heterogeneity and linkage

## Solution Statement
This project integrates hydrological data analysis, modeling tools, and digital workflows to better understand and visualize water system behavior in subarctic catchments.

## Objectives
1. Analyze hydrological datasets.
2. Apply reproducible data science workflows.
3. Investigate soil moisture dynamics.
4. Develop visualization tools for environmental data.
5. Ensure reproducibility using Git and structured workflows.
---
# Literature Review
- Freeze & Harlan (1969) – Blueprint for physically-based hydrological modeling  
- Marttila et al. (2021) – Subarctic catchment hydrology in Pallas  
-Nousu et al. (2024) – Soil moisture modeling in Pallas
---
# Research Questions
The planned analyses focus on the following research questions:
1.	How do spatial and temporal patterns of soil moisture vary across the Pallas Lake catchment at the landscape scale?
2.	How do lateral groundwater flow and snowmelt processes influence soil moisture regimes and their spatial distribution?
3.	How well does SpaFHy-2D reproduce observed soil moisture patterns when evaluated against soil moisture datasets?
4.	How sensitive are simulated soil moisture dynamics to groundwater and snow process representations under contrasting hydrometeorological conditions?
---

# Data Sources

- Meteorological forcing data
- Soil moisture measurements
- Stream discharge records

(Data stored in `ClassData/` folder.)

---

# Methods

- Data preprocessing in Python
- Statistical analysis
- Hydrological modeling – Spatial Forest Hydrological Model (SpaFHy-2D)
- Visualization using matplotlib
- Version control with Git

---

# Repository Structure

WaterDig/
│
├── ClassData/        # Input datasets
├── CodeSprints/      # Jupyter notebooks and exercises
├── README.md
└── MIT License
Citation:
Parvizi, P. (2026). WaterDig Repository. https://github.com/Parspar/WaterDig
---

# Reproducibility
Results Summary
•	Reproducible hydrological workflows created
•	Improved understanding of soil moisture dynamics in northern regions
•	Structured digital water research repository

## Run in CSC JupyterHub

1. Open Jupyter environment
2. Navigate to CodeSprints/
3. Run notebooks sequentially

## Run Locally

```bash
git clone https://github.com/Parspar/WaterDig.git
cd WaterDig
pip install -r requirements.txt
