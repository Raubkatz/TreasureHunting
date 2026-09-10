# TreasureHunting

## Installation

A dedicated environment is recommended. The following pinned environment can be used for the complete Austria Treasure AI pipeline:

```text
python==3.12.14

numpy==2.5.3
scipy==1.18.1
pandas==3.0.5
scikit-learn==1.9.0
joblib==1.6.0

catboost==1.2.10
xgboost==3.4.1
lightgbm==4.7.0
optuna==4.9.0
imbalanced-learn==0.14.2

rasterio==1.5.1
geopandas==1.1.4
shapely==2.1.2
pyproj==3.8.0
pyogrio==0.13.0
rioxarray==0.23.0
xarray==2026.7.0
dask==2026.7.0
zarr==3.3.0
fsspec==2026.7.0

pystac==1.15.2
pystac-client==0.9.0
requests==2.34.2

matplotlib==3.11.1
contextily==1.7.1
folium==0.20.0
xyzservices==2026.3.0
geopy==2.5.0

shap==0.52.0
tqdm==4.70.0
```

Create and activate the environment:

```bash
conda create -n treasure_ai python=3.12.14
conda activate treasure_ai
```

Install all packages required by the complete satellite-data, geospatial-processing, machine-learning, candidate-ranking, and mapping pipeline:

```bash
pip install \
    numpy==2.5.3 \
    scipy==1.18.1 \
    pandas==3.0.5 \
    scikit-learn==1.9.0 \
    joblib==1.6.0 \
    catboost==1.2.10 \
    xgboost==3.4.1 \
    lightgbm==4.7.0 \
    optuna==4.9.0 \
    imbalanced-learn==0.14.2 \
    rasterio==1.5.1 \
    geopandas==1.1.4 \
    shapely==2.1.2 \
    pyproj==3.8.0 \
    pyogrio==0.13.0 \
    rioxarray==0.23.0 \
    xarray==2026.7.0 \
    dask==2026.7.0 \
    zarr==3.3.0 \
    fsspec==2026.7.0 \
    pystac==1.15.2 \
    pystac-client==0.9.0 \
    requests==2.34.2 \
    matplotlib==3.11.1 \
    contextily==1.7.1 \
    folium==0.20.0 \
    xyzservices==2026.3.0 \
    geopy==2.5.0 \
    shap==0.52.0 \
    tqdm==4.70.0
```
