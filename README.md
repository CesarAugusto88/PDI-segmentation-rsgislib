# PDI-segmentation-rsgislib

Install rsgislib in conda:
```
conda activate

conda create -n rsgislib -c conda-forge python=3.10 \
rsgislib gdal rasterio fiona geopandas shapely rtree rasterstats \
h5py scikit-learn scikit-image scikit-optimize imbalanced-learn \
matplotlib pandas statsmodels scipy networkx sqlalchemy pycurl \
xgboost lightgbm tpot seaborn numba pip sphinx elevation tqdm \
jinja2 keras keras-preprocessing pytables bokeh pygal jupyterlab \
psutil pysal libpysal esda pyyaml netcdf4 xarray plotly \
python-kaleido psycopg2 ipywidgets tuiview jupyter --strict-channel-priority

conda activate rsgislib

jupyter notebook
``` 
Instructions on installing RSGISLib: [rsgislib](https://github.com/remotesensinginfo/rsgislib)
