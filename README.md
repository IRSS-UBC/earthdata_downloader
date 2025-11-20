# earthdata_downloader
Jupyter notebook script for batch downloading collections from earthdata. The notebook is set up to download your data based on a provided tiling shapefile. 

Access credentials are needed - freely available at https://urs.earthdata.nasa.gov/.

Collections are specified using the short names, available at https://www.earthdata.nasa.gov/centers/lp-daac/data-access-tools. 

This script is a basic working example of the earthaccess python package. (Documentation: https://pypi.org/project/earthaccess/)

Full set-up:

conda create --prefix "path/folder/earthdata_env" python=3.11 -y
conda activate "path/folder/earthdata_env"
conda install -c conda-forge earthaccess
python -m pip install --upgrade geopandas shapely

Move the earthaccess_download.ipynb notebook into your environment folder, and then launch:
jupyter lab "path/folder/earthdata_env/earthaccess_download.ipynb"

After you have set up your environment, if you want to revisit this later:

conda activate "path/folder/earthdata_env"
jupyter lab "path/folder/earthdata_env/earthaccess_download.ipynb"



