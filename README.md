# Assessment of Soil Microplastic Contamination: Distribution, Soil Properties, and Agricultural Practices

BDS3106 Programming for Data Science, Mid-Term Project (Phase I), Fall 2026–2027, AIUB
Team: 24-59774-3, 24-59701-3, 25-61638-1, 24-58964-2

## Overview
Exploratory analysis of a real five-country agricultural soil survey (China, Egypt, India, Sri Lanka, Vietnam). We study how microplastic (MP) abundance varies by country and soil depth, how it relates to soil properties and reported farm practices, which polymers are identified, and how reliable the measurements are. Results describe associations only, not causes.

## Dataset
Graf, M.; Chadwick, D.R.; Jones, D.L. (2026). *Agricultural soil survey and inter-laboratory comparison of microplastics across China, Egypt, India, Sri Lanka, and Vietnam, 2022-2025.* NERC EDS Environmental Information Data Centre. https://doi.org/10.5285/c0407da7-acd0-4f5f-a1f3-5516206ba787
Licence: Open Government Licence v3. Attribution: "Contains data supplied by UK Centre for Ecology & Hydrology."
The data are not included here. Download them from the DOI and put the CSV files in `data/`.

## Files
- `soil_microplastic.ipynb` – loading, validation, preprocessing, EDA and figures
- `raw data` – raw CSV files (download separately)
- `figures`, `tables/` – outputs created by the notebook
- `report` – project report
- `supporting-document`- supporting documents
- `ro-crate-metadata.json` - metadata

## Dependencies and how to run
Python 3.9+, pandas, numpy, matplotlib, seaborn, jupyter (`pip install pandas numpy matplotlib seaborn jupyter`).
1. Put the CSV files in `raw data/`.
2. Open `soil_microplastic.ipynb` and choose Restart & Run All.

## Member contributions
- 24-59774-3: Problem definition, preprocessing, background study.
- 24-59701-3: Visualization.
- 25-61638-1: Exploratory Data analysis, preprocessing.
- 24-58964-2: Dataset finding, research questions, report wrting.
