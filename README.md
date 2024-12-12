# enterprise

This is Yonghao's fork of ENTERPRISE. Not Official.

ENTERPRISE (Enhanced Numerical Toolbox Enabling a Robust PulsaR
Inference SuitE) is a pulsar timing analysis code, aimed at noise
analysis, gravitational-wave searches, and timing model analysis.

-   Note: `enterprise>=3.0` does not support Python2.7. You must use
    Python \>= 3.8.
-   Free software: MIT license
-   Documentation: <https://enterprise.readthedocs.io>.

## Installation

To install via `pip`, some non-python dependencies are required. See the
[libstempo](https://github.com/vallis/libstempo#pip-install) and
[scikit-sparse](https://github.com/scikit-sparse/scikit-sparse#with-pip)
documentation for more info on how to install these dependencies. Once
these are installed, you can do

```bash
pip install enterprise-pulsar
```

To install via `conda`, simply do

```bash
conda install -c conda-forge enterprise-pulsar
```

## Attribution

If you make use of this software, please cite it:

    Ellis, J. A., Vallisneri, M., Taylor, S. R., & Baker, P. T. (2020, September 29). ENTERPRISE: Enhanced Numerical Toolbox Enabling a Robust PulsaR Inference SuitE (v3.0.0). Zenodo. http://doi.org/10.5281/zenodo.4059815


    @misc{enterprise,
      author       = {Justin A. Ellis and Michele Vallisneri and Stephen R. Taylor and Paul T. Baker},
      title        = {ENTERPRISE: Enhanced Numerical Toolbox Enabling a Robust PulsaR Inference SuitE},
      month        = sep,
      year         = 2020,
      howpublished = {Zenodo},
      doi          = {10.5281/zenodo.4059815},
      url          = {https://doi.org/10.5281/zenodo.4059815}
    }

## Credits

This package was created with
[Cookiecutter](https://github.com/audreyr/cookiecutter) and the
[audreyr/cookiecutter-pypackage](https://github.com/audreyr/cookiecutter-pypackage)
project template.
