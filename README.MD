# Cincinnati Shootings Data Analysis (2022-2025)

## Overview
This project analyzes Cincinnati Police Department shooting reports from 2022 through 2025. It explores patterns by **year**, **race**, **neighborhood**, **age ranges**, **sex**, and **type of shooting**, focusing on data cleaning and visualization.

## Dataset
The dataset is sourced from the official [City of Cincinnati Open Data Portal](https://data.cincinnati-oh.gov/safety/CPD-Reported-Shootings/sfea-4ksu/about_data). It includes shooting incidents with attributes such as:

- District, Neighborhood
- Date and Time of Incident
- Victim Demographics: Age, Race, Sex
- Incident Details: Type of Shooting, Threat Level

## Key Steps

### 1. Data Cleaning
- Dropped rows with missing critical values (e.g., location, neighborhood).
- Created new categorical columns like `AgeRange` for easier analysis.

### 2. Data Exploration
- Yearly shooting counts and shooting rates per 100,000 population.
- Shooting distributions by **race** and **neighborhood**.
- Grouped shootings by **age ranges** (e.g., 18-25, 26-32) combined with race, sex, and type.

### 3. Visualizations
- Bar charts with counts and percentages.
- Age range vs. race shooting distribution charts.

## Dependencies
- Python 3.x
- pandas
- matplotlib
- numpy

Install dependencies with:
```bash
pip install pandas matplotlib numpy
