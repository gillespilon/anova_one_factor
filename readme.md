[![Coverity Scan Build Status](https://img.shields.io/coverity/scan/10257.svg)](https://scan.coverity.com/projects/gillespilon-anova_one_factor)
[![Travis](https://img.shields.io/travis/rust-lang/rust.svg)](https://travis-ci.org/gillespilon/anova_one_factor)

# In brevi

This repository contains two notebooks: one performs a one-factor analysis of variance (ANOVA) and the other estimates quartiles using the nine known methods found in the literature. The latter notebook arose while comparing results of the first notebook with Minitab statistical software, which led to questions of why the difference.

This repository is incomplete. Future work is ongoing.

# Methodology

Various data munging operations are performed using pandas. Various statistical analyses are performed using statsmodels, scipy, and numpy.

# Data

Download the  file:

- [estimating_quartiles.csv](https://drive.google.com/open?id=1Nc_VFXo2SrsSdprfCmQYhLbJawAzKpH6)

# References

[pandas](https://pandas.pydata.org/pandas-docs/stable/index.html)

[statsmodels](https://www.statsmodels.org/stable/index.html)

[scipy](https://docs.scipy.org/doc/scipy/reference/)

[numpy](https://docs.scipy.org/doc/numpy/reference/)
