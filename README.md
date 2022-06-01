# Conda Packages for FFTW3

## Specs

FFTW3 3.3.10 compiled with OpenMP and MPI support. Disabled shared flag.

##  Installation

This package requires the conda-forge channel. There are two ways to install this package:

1. Use the Conda-forge channel directly in the install command:

```
conda install -c i4ds -c conda-forge FFTW3 
```

2. Append the Conda-forge channel first - if you need it anyway, or multiple times:

```
conda config --append channel conda-forge
conda install -c i4ds FFTW3 
```

## Information about FFTW3

https://github.com/FFTW/fftw3

## Why Conda?
To enable a simple Installation, with no compilation or other inconveniences, conda is the perfect platform for scientific computing. As FFTW3 has a c++ backend, meaning compilation is required. Conda allows us to do so and bundle all dependencies very easily and distribute them to the users.
