# Lompe documentation

View at <https://smithara.github.io/lompe-docs/>

## Building locally

First get the submodules:
```
git submodule update --init --recursive
```

or update them to their latest remote versions:
```
git submodule update --init --recursive --remote
```

Create an environment for the build:
```
mamba env create -f environment.yml -n lompe-docs
mamba activate lompe-docs
```

then run:
```
make -C docs clean; make -C docs html
```

You might also `rm -rf docs/reference/` in between builds (related to `sphinx.ext.autosummary`)
