# Obtaining the input data for the global, GOLD\_SIS and CM2G-class experiments #

The data has been provided in tar-balls grouped together for each experiment. The initial conditions and forcing are already interpolated to the appropriate model grids ready to use with the model. This means that in most instances you will find (interpolation) differences with the original source data.

You can use anonymous ftp using your favorite ftp client or, if you use unix, use the wget command line tool as follows:

```
wget ftp.gfdl.noaa.gov:/perm/GOLD/pubrel1/global_input.tar.gz
wget ftp.gfdl.noaa.gov:/perm/GOLD/pubrel1/GOLD_SIS_input.tar.gz
wget ftp.gfdl.noaa.gov:/perm/GOLD/pubrel1/CM2G63L_input.tar.gz
wget ftp.gfdl.noaa.gov:/perm/GOLD/pubrel1/WOA05_pottemp_salt.nc
```