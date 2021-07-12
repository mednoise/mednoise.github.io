# <img alt="mednoise" src="/_static/logo.png" height="60">

[![Downloads](https://pepy.tech/badge/mednoise)](https://pepy.tech/project/mednoise)
[![Version](https://img.shields.io/badge/version-1.2.4-orange)](https://pepy.tech/project/mednoise)
[![Dependencies](https://img.shields.io/badge/dependencies-up%20to%20date-brightgreen)](https://pepy.tech/project/mednoise)


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
