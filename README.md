# pvpmc2024
2024 PVPMC Workshop in Salt Lake City, UT, USA

## PVfit Tutorial

### Python Environment and Package Installation

Set up a Python 3.10-12 virtual environment---
```console
  $ python -V
  Python 3.11.7
  $ python -m venv pvfit_pvpmc2024
  $ . pvfit_pvpmc2024/bin/activate
  $ python -m pip install --upgrade pip setuptools
```

Install `pvfit v0.0.1` from PyPI with `demo` dependencies---
```
  $ python -m pip install pvfit[demo]==0.0.1
  $ python -c "from pvfit import __version__; print(__version__)"
  0.0.1
```

### Tutorial Notebook Setup


Install `jupyterlab`` for interactive tutorials---
```console
$ python -m pip install jupyterlab
```

Run `jupyterlab`` within a web browser (or VSCode, etc.)---
```
  $ jupyter lab
```

This presentation follows these Jupyter notebooks from https://github.com/markcampanelli/pvpmc2024/tutorial---
- [1_single_diode_model_calibration.ipynb](tutorial/1_single_diode_model_calibration.ipynb)
- [2_dc_performance_prediction.ipynb](tutorial/2_dc_performance_prediction.ipynb)
- [3_flex_your_model!.ipynb](tutorial/3_flex_your_model!.ipynb)
