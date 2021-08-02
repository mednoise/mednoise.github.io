# <img alt="mednoise" src="/_static/logo.png" height="60">

[![Downloads](https://img.shields.io/pypi/dm/mednoise?color=blue&style=flat-square)](https://pypi.org/project/mednoise/)
[![Version](https://img.shields.io/pypi/v/mednoise?color=orange&label=version&style=flat-square)](https://pypi.org/project/mednoise/)
[![License](https://img.shields.io/github/license/mednoise/mednoise?color=red&label=license&style=flat-square)](https://github.com/mednoise/mednoise/blob/main/LICENSE)
[![Paper](https://img.shields.io/badge/JOSS-Submitted-blueviolet?style=flat-square)](https://joss.theoj.org/papers/e334cd1cbcdde8c9aa37254eb5c6bfec/)

##### Summary 

mednoise is the fundamental package needed for medical image (pre)processing with Python.

- **Website:** https://mednoise.github.io
- **PyPI:** https://pypi.org/project/mednoise/
- **Documentation:** https://mednoise.github.io/documentation
- **Source code:** https://github.com/mednoise/mednoise
- **Bug reports:** https://github.com/mednoise/mednoise/issues

It contains:
- various algorithms to handle and pre-process large amounts of medical image metadata
- a highly tuneable interface for a variety of  usecases
- an inference-compatible structure that allows for easy integration into workflow/pipeline management systems (ex. airflow, luigi, snakemake)

##### Installation:

mednoise uses `pip`.  The installation can be run with:

    pip install mednoise

The dependencies for mednoise are  `glob2`, `numpy`, `pillow`, and `scipy`. Please try installing those manually if you reach an error.
   
##### License

mednoise is licensed under the `Apache 2.0 License`
