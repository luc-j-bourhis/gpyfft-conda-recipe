# Conda recipe for Python package `gpyfft`

Recipe page: https://anaconda.org/ljbo3/gpyfft

## Build

From the top directory,

```
% conda build -c defaults -c conda-forge .
```

We need conda-forge for `clfft` and `pyopencl`.

## Install

```
% conda -c ljbo3 gpyfft
```
