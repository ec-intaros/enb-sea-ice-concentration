# Sea ice concentration statistics
Tool for generating monthly mean sea ice concentration for the Svalbard region.

## Introduction
This tool uses daily products from the *Copernicus Marine Environment Monitoring Service* (CMEMS) to generate monthly mean values of sea ice concentration for the Svalbard region. The daily products are accessed using the OPeNDAP protocol and the resulting sea ice statistics is stored in a NetCDF file.

## Installation

The tool requires the following software to run:
- Jupyter Notebook (Available at: https://jupyter.org)
- Python 3 (Available at: https://python.org/)
- netcdf4 (Available at: https://github.com/Unidata/netcdf4-python)
- matplotlib (Available at: https://matplotlib.org/)

Install the required software. Download the source code files in this repository and add them to a folder that you can open in Jupyter Notebook. The whole repository can be downloaded using `git clone https://gitlab.com/ec-intaros/applications/ewf-sea-ice-concentration`.


## Usage
Start the Jupyter Notebook by typing `jupyter notebook` in a terminal, and open the notebook. Run through the cells of the notebook, entering the year and month you want to generate the mean sea ice concentration  (SIC) for.

The resulting monthly mean SIC is stored in a NetCDF file, and a simple plot of the SiC field is generated and stored in a PNG file.

## References
[1] CMEMS PRODUCT USER MANUAL (CMEMS-SI-PUM-011-002) https://marine.copernicus.eu/documents/PUM/CMEMS-SI-PUM-011-002.pdf 

[2] netcdf4 module documentation: https://unidata.github.io/netcdf4-python/netCDF4/index.html 

[3] matplotlib tutorials: https://matplotlib.org/tutorials/index.html

[4] Open-source Project for a Network Data Access Protocol (OPeNDAP) http://www.opendap.org/ 

## Authors
Torill Hamre (NERSC)

## Licenses
This work is licensed under a Creative Commons Attribution 4.0 International License. http://creativecommons.org/licenses/by/4.0/

## Acknowledgements
This project has received funding from the European Union's Horizon 2020 research and innovation programme under grant agreement No 727890.


