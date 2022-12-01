# PDI-segmentation-rsgislib

Install rsgislib in conda (Linux):
```
conda activate

conda create -n rsgislib -c conda-forge rsgislib python=3.10

conda deactivate

conda activate rsgislib 

conda install -c conda-forge rsgislib gdal h5py parallel scikit-learn scikit-image scikit-optimize imbalanced-learn matplotlib pandas geopandas statsmodels scipy rasterio shapely networkx sqlalchemy pycurl xgboost lightgbm tpot seaborn numba pip sphinx elevation rtree tqdm jinja2 keras keras-preprocessing pytables bokeh pygal jupyterlab psutil pysal libpysal esda pyyaml netcdf4 xarray rasterstats fiona plotly python-kaleido psycopg2 ipywidgets tuiview jupyter

jupyter notebook
``` 
Instructions on installing RSGISLib: [rsgislib](https://github.com/remotesensinginfo/rsgislib)
