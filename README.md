# Exploration of the Python Pangeo Stack

NOTE: I have not included the source data in this repository, so please only view these as static notebooks. 

If you wish to download the data and use these notebooks dynamically, take the following steps:

1) Download these three netCDF files into a folder located at `root/data/2017` 
- https://datapub.fz-juelich.de/slts/cordex/data/pgw/
     - pgw_EUR-11_ECMWF-ERAINT_evaluation_r1i1p1_FZJ-IBG3-TERRSYSMP11_v1_day_20170101-20171231.nc	
- https://datapub.fz-juelich.de/slts/cordex/data/sgw/
     - sgw_EUR-11_ECMWF-ERAINT_evaluation_r1i1p1_FZJ-IBG3-TERRSYSMP11_v1_day_20170101-20171231.nc	
- https://datapub.fz-juelich.de/slts/cordex/data/wtd/
     - wtd_EUR-11_ECMWF-ERAINT_evaluation_r1i1p1_FZJ-IBG3-TERRSYSMP11_v1_day_20170101-20171231.nc	

2) First run all cells in `tsmp-data-cleanup.ipynb`
- This will create a new file called `iberian.nc`

3) You're now free to run `iberian-eda.ipynb` as it takes `iberian.nc` as its input.


## Sources Cited:
Registry of data: https://www.re3data.org/repository/r3d100012923 <br>
Link to full data repository: https://datapub.fz-juelich.de/slts/cordex/ <br>
Publication used to find data: https://www.nature.com/articles/s41597-019-0328-7
