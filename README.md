TTools2 
======

## About

TTools is a collection of python scripts used to sample and assemble stream channel and land cover geospatial data for input into the [Heat Source][1] model, Washington Department of Ecology's [Shade][2] model, or the shade input file for [CE-QUAL-W2][3].

TTools was originally developed for Esri ArcGIS 10.1 - 10.8.2, requiring Python 2.7 and Esri's arcpy library. TTools2 uses the same five script workflow, but utilizes the advantages of Python 3, open source geospatial tools from [geopandas][4] and [rasterio][5], and numpy vector operations to improve performance on modern python environments.


TTools2 is a work in progress.

Developed using Python 3.XX, geopandas XX, and numpy XX. See the environment.yml file to create an Anaconda environment with the exact packages, or to reference other package versions.



[1]: https://github.com/DEQrmichie/heatsource-9
[2]: https://ecology.wa.gov/Research-Data/Data-resources/Models-spreadsheets/Modeling-the-environment/Models-tools-for-TMDLs
[3]: http://www.ce.pdx.edu/w2/
[4]: https://github.com/geopandas/geopandas
[5]: https://github.com/rasterio/rasterio
