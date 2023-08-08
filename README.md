# NYC-Tree-Census
This project is a exploratory data analysis (EDA) with python of the 2015 New York City Street Tree Census dataset that is available on NYC Open Data. The analysis explores the species, health, size, and geolocation of trees living on NYC streets. The project identifies the most common tree species and using geopandas plots their geolocation on a map of New York City's five boroughs.


## Files

* `notebooks/2015_Street_Tree_Census_Tree_Data_Visualization.ipynb` - Jupyter notebook, the exploratory analysis.
* `data/2015_Street_Tree_Census_-_Tree_Data.csv` - The 2015 NYC Street Tree Census dataset.
> data source: https://data.cityofnewyork.us/Environment/2015-Street-Tree-Census-Tree-Data/uvpi-gqnh
* `data/nyc_borough_boundaries/` - Directory containing the shape files with NYC borough boundaries.
> shape file source: https://data.cityofnewyork.us/City-Government/Borough-Boundaries/qefp-jxjk

## Dependencies
```
python 3.9.7
pandas 1.4.1
numpy 1.22.2
matplotlib 3.5.1
seaborn 0.11.2
geopandas 0.10.2
shapely 1.8.1
```