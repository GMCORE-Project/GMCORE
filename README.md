# Introduction

Grid-point Multiple-Conservation dynamical cORE

Check barotropic test results [here](https://github.com/gmcore-project/gmcore/wiki/Test-Archive).

# Usage

First make sure you have installed netCDF library, and set `NETCDF_ROOT` environment variable to it. Then clone the repository:
```
$ git clone https://github.com/LASG-GAMIL/GMCORE gmcore
```
There is a shell script `run_tests.sh`, which will clone the submodules, compile the model and run several tests:
```
$ ./run_tests.sh <work_directory>
```
It will take some time to run the tests. When the tests are finished, cd to `<work_directory>`, and use some visualization tools, such as Panoply, to view the results.
