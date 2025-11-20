# earthdata_downloader

Jupyter notebook script for batch downloading collections from earthdata. The notebook is set up to download your data based on a provided tiling shapefile.

-   Access credentials are needed - freely available at <https://urs.earthdata.nasa.gov/>.

-   Collections are specified using the short names, available at <https://www.earthdata.nasa.gov/centers/lp-daac/data-access-tools>.

-   This script is a basic working example of the earthaccess python package. (Documentation: <https://pypi.org/project/earthaccess/>)

**Full set-up:**

1.  conda create --prefix "path/folder/earthdata_env" python=3.11 -y

2.  conda activate "path/folder/earthdata_env"

3.  conda install -c conda-forge earthaccess

4.  python -m pip install --upgrade geopandas shapely jupyterlab ipywidgets

(Move the earthaccess_download.ipynb notebook into your environment folder)

5.  jupyter lab "path/folder/earthdata_env/earthaccess_download.ipynb"

After you have set up your environment, if you want to revisit this later:

1.  conda activate "path/folder/earthdata_env"

2.  jupyter lab "path/folder/earthdata_env/earthaccess_download.ipynb"
