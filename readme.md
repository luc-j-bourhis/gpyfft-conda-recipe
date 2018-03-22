# Conda recipe for Python package `gpyfft`

This packages the work of [Gregor Thalhammer](https://github.com/geggo), which can be found in [this repository of his](https://github.com/geggo/gpyfft).

## Build

From the top directory,

```
conda build -c defaults -c conda-forge .
```

We need conda-forge for `clfft` and `pyopencl`.

## Install

From this [Anaconda page](https://anaconda.org/ljbo3/gpyfft) of mine, or directly on the command-line

```
conda -c ljbo3 gpyfft
```
