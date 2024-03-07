## Afrikan_Parks_Chad_ACLED

## Overview

ACLED Data and visualizations of the security events in and around Afrikan Parks prior to Afrikan Parks management and during Afrikan Parks managament. The prupose of these visuals is to gain an understanding of how the security events developed and changed after Afrikan Parks took over management of Zakouma National Park. Exploring the trends in the park and the 5km, 20km buffer zones and how they relate to the trends of the surrounding areas and Chad.

## Project Structure

1. **Zakouma_vs_Chad.ipynb**: The Jupyter Notebook containing the code for data analysis, visualizations.

2. **Maps**: This directory includes HTML files containing interactive maps generated during the analysis.

3. **Visualizations**: Copies of the visualizations saved as png.

4. **Chad and DRC.zip**: Contains dataset in CSV format.


## Installation
Python 3.11 -  https://www.python.org/downloads/, 
Anaconda -  https://www.anaconda.com/download/
pip install pandas, 
pip install numpy, 
pip install geopandas, 
pip install shapely, 
pip install sklearn, 
pip install matplotlib, 
pip install seaborn, 
pip install IPython, 
pip install folium, 


## Usage
launch Anaconda
launch Jupyter Notebook
import pandas as pd
import numpy as np
import geopandas as gpd
from shapely.geometry import Point
from sklearn.cluster import KMeans
import matplotlib.pyplot as plt
import seaborn as sn
from sklearn.linear_model import LinearRegression
from IPython.display import HTML, display, IFrame
import folium
from folium.plugins import MarkerCluster

## Contributors

Jan Hendrik Hofmeyr

## Acknowledgments

Source: Armed Conflict Location & Event Data Project (ACLED); www.acleddata.com
