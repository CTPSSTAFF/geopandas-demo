# geopandas-demo

## Overview
The contents of this repository demonstrate the use of the Python [__geopandas__](https://geopandas.org) package to perform a simple, but common, geo-processing task: 
_calculate the total area, in square miles, of the one-quarter mile service area of all MBTA Red Line heavy rail rapid transit stations_.

## Dependencies
This demo requires version 0.10.0 \(or higher\) of geopandas, because it uses the relatively new _explore_ GeoDataFrame method to render maps.
This, in turn, requires the use of Python version 3.10 \(or higher\).

## Running the Demo
The __geopahdas_demo.ipynb__ Jupyter notebook should be run under the Anaconda environment specified in the py_3_10.yml file.  
To create this environment in an Anaconda shell:
```
conda env create -f py_3_10.yml
```
Then:
* launch Jupyter Notebooks using the py_3_10 environment
* open the notebook __geopahdas_demo.ipynb__, and
* execute its contents

## Colophon
Author: Ben Krepp (bkrepp@ctps.org)  
Last revision: 13 February 2023  
Location: Cyberspace
