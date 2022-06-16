![Logo Dark](docs/source/_static/cp_logo_dark.png#gh-dark-mode-only)
![Logo Light](docs/source/_static/cp_logo.png#gh-light-mode-only)

[![Run Tests](https://github.com/robbievanleeuwen/concrete-properties/actions/workflows/tests.yml/badge.svg)](https://github.com/robbievanleeuwen/concrete-properties/actions/workflows/tests.yml) [![Lint with Black](https://github.com/robbievanleeuwen/concrete-properties/actions/workflows/black.yml/badge.svg)](https://github.com/robbievanleeuwen/concrete-properties/actions/workflows/black.yml) [![Build Documentation](https://github.com/robbievanleeuwen/concrete-properties/actions/workflows/build_docs.yml/badge.svg)](https://robbievanleeuwen.github.io/concrete-properties/) [![PyPI version](https://badge.fury.io/py/concreteproperties.svg)](https://badge.fury.io/py/concreteproperties) [![Python versions](https://img.shields.io/badge/python-3.7%20%7C%203.8%20%7C%203.9-blue?style=flat&logo=python)](https://badge.fury.io/py/concreteproperties) [![GitHub license](https://img.shields.io/github/license/robbievanleeuwen/concrete-properties)](https://github.com/robbievanleeuwen/concrete-properties/blob/master/LICENSE.md)

Calculate section properties for reinforced concrete sections.

```shell
pip install concreteproperties
```

## To do:
- [x] Expand material properties
  - [x] Tensile strength
  - [x] Residual shrinkage tensile stress
- [ ] Add concrete property calculations
  - [x] Gross second moment of area (I_g)
  - [x] Cracking moment (M_cr)
  - [ ] Cracked second moment of area (I_cr)
  - [ ] Effective second moment of area (I_ef)
  - [ ] Reporting of k_u
- [ ] Add stress calculations
  - [ ] Uncracked stresses
  - [ ] Cracked stresses
  - [ ] Stresses at ultimate
- [ ] Add code module
  - [ ] Codify calculation of material properties
- [ ] Add visualisation
  - [ ] Stress visualisation
  - [ ] Free body diagrams
- [x] Exclude holes made by reinforcement in ultimate calculation

## Current limitations:
- Can only have only value of ultimate concrete strain

## Assumptions
- Compression (+ve); Tension (-ve)
