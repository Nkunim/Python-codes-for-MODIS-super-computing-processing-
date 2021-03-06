My python codes for research.

Main topics:

1. Remote sensing data processing
2. GDAL, Numpy packages
3. MODIS data hdf, geotiff
4. Multi cores supercomputing

This python codes use gdal, python and numpy open source pachages to process MODIS mod09a1 tile data to generate Vegetation Index, drought, 
everreen, ocean, snow, cloud, flood products.

Vegetation indices, quality flag and land/ocean mask from multiple tiles

This is used to process all the tiles at a specific 8-day observation.

The advanced version code use python multi run jobs functioin to run on multi-threads on our supercomputing servers. The global 2000 to 2013 8-days MODIS data can be finished in 168 hours from raw data to final products.

Input data: HDF
Functions:
Calculate vegetation indices,
Decode quality flag
Decode ocean flag
Decode snow flag
produce drought, evergreen, flood

This use 8x16x10 cores on our high performence servers. 

Loop through all the tiles

Output data: geotiff of different products.

![alt tag](https://raw.github.com/zhaodelong/Python-codes-for-MODIS-super-computing-processing-/master/modis%20processing%20workflow.png)


Delong Zhao

Research assistant
Earth Observation and Modeling Facility (EOMF)
Center for Spatial Analysis, College of Atmospheric and Geographic Sciences
University of Oklahoma
101 David L. Boren Blvd.
Norman, Oklahoma 73019-5300
USA
Phone:405-355-3066 
Email: zhaodelong@gmail.com;                       Skype:  zhaodelong_ioz
Websites:  http://eomf.ou.edu/
