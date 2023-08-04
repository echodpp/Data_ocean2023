`Cr Compilation filtered Apr23.xlsx` is the raw data we used when we explored the relationship between Chromium concentrations and NCP, and `cleaned.xlsx` is the same dataset but has undergone basic data cleaning. `matched-seawifs-8day-ncp-12-6-2012.xlsx` is the original dataset used in building the machine-learning models to estimate the NCP, which has already been a cleaned version with satellite image data merged into it.

Sources of the five parameters (NPP, CHL, SST, PAR, and MLD) from the satellite image data are listed below:

1. NPP:
SeaWiFS: http://orca.science.oregonstate.edu/1080.by.2160.monthly.hdf.vgpm.s.chl.a.sst.php
MODIS: http://orca.science.oregonstate.edu/1080.by.2160.monthly.hdf.vgpm.m.chl.m.sst.php
2. CHL:
SeaWiFS: http://orca.science.oregonstate.edu/1080.by.2160.monthly.hdf.chl.seawifs.php 
MODIS: http://orca.science.oregonstate.edu/1080.by.2160.monthly.hdf.chl.modis.php
3. SST:
SeaWIFS: http://orca.science.oregonstate.edu/1080.by.2160.monthly.hdf.sst.avhrr.php 
MODIS: http://orca.science.oregonstate.edu/1080.by.2160.monthly.hdf.sst.modis.php 
4. PAR:
SeaWIFS: http://orca.science.oregonstate.edu/1080.by.2160.monthly.hdf.par.seawifs.php 
MODIS: http://orca.science.oregonstate.edu/1080.by.2160.monthly.hdf.par.modis.php 
5. MLD:
http://orca.science.oregonstate.edu/1080.by.2160.monthly.hdf.mld030.hycom.php
