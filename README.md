# Bender feedstock

This repository contains the necessary recipe to create a conda package for [bender](https://github.com/pulp-platform/bender).

## Use this package

### conda

```sh
conda install bender -c kuleuven-micas
```

### pixi

Add this to your `pixi.toml`

```toml
[project]
...
channels = ["conda-forge","kuleuven-micas"]
...
[dependencies]
...
bender = "*"
```

## Build requirements

To build this package locally, you'll need an environment with:
* `conda` or `pixi`
* `anaconda-client`
* `rattler-build`
* `git`


