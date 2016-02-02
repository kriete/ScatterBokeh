# ScatterBokeh
An ipython notebook. Also view on http://nbviewer.jupyter.org/github/kriete/ScatterBokeh/blob/master/ScatterBokeh.ipynb

## Purpose
The idea is to generate a bokeh graph to interactively explore 2.5 dimensional scattered data from a netCDF document.

On the basis of a netCDF document, an easy reproduceable example will be demonstrated. In the code showed below, we will produce a temperature-salinity diagram with colored chlorophyll data as z-data axis.

If needed, the whole code can be wrapped into an own package.

The data comes from the publicity available socib data (www.socib.es).

## Dependencies
This example is based upon the following python packages:

numpy
matplotlib
bokeh
netCDF4
Where the use of numpy, matplotlib and netCDF4 can be skipped, if the data (including color-codes) is coming from other sources.
