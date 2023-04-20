# Lompe Documentation

<!-- Project background -->
```{toctree}
intro
```

<!-- API reference generated from docstrings -->
```{eval-rst}
.. autosummary::
    :recursive:
    :toctree: reference
    :caption: Lompe reference

    lompe.data_tools
    lompe.model
    lompe.utils

.. autosummary::
    :recursive:
    :toctree: reference
    :caption: Sub-packages reference

    lompe.dipole
    lompe.polplot
    lompe.secsy

```

<!-- Notebook-based examples -->
```{toctree}
:caption: Examples
:glob:
examples/*
```

```{toctree}
:caption: Examples... code_paper_figures
:glob:
examples/code_paper_figures/*
```

```{toctree}
:caption: Examples... lompe_paper_figures
:glob:
examples/lompe_paper_figures/*
```

```{toctree}
:caption: Examples... experimental
:glob:
examples/experimental/*
```
