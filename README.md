# [View the Map of Kenya here](https://gathuh.github.io/CENSUS-2020-MODEL/)# Population Density Heatmap Project

## Overview

This project visualizes population density data for various subcounties in Kenya using Folium, a Python library for creating interactive maps. The data includes the total population, male and female counts, area in square kilometers, and population density for each subcounty.

## Features

- Interactive heatmap displaying population density across subcounties.
- Visualization is created using the Folium library, which generates HTML maps.

## Data

The dataset contains the following columns:

- **County**: The name of the county.
- **Subcounty**: The name of the subcounty.
- **Total**: Total population.
- **Male**: Number of males.
- **Female**: Number of females.
- **SQ.Km**: Area in square kilometers.
- **Population_density**: Population density (people per square kilometer).
- **Latitude**: Latitude of the subcounty.
- **Longitude**: Longitude of the subcounty.

## Requirements

To run this project, you will need the following Python packages:

- pandas
- folium

You can install these packages using pip:

```bash
pip install pandas folium
