# taming-bad-python-packages
This repository contains the source code and data for the blog post "Taming Bad Python Packages Assessing Python Malware Detectors with a Benchmark Dataset"
The main objective is to evaluate the [PyPI Malware Checks](https://warehouse.pypa.io/development/malware-checks.html) on three datasets of malicious, popular and random PyPI packages.

The blog post is available at [here](https://blog.chainguard.dev/taming-python-malware-scanners/). The blog is also covered by darkreading at [here](https://www.darkreading.com/application-security/one-third-pypi-packages-mistakenly-flagged-malicious)

You can find in this repository:
- [scanning results files](results/): the scanning results of PyPI Malware Checks on the three datasets in Pickle format.
- [A jupiter notebook](pypi-malware-checks-analysis.ipynb): this will analyze the scanning results and produce statistics about the performance of each tool. 

To install the dependencies of this project, we use [Poetry](https://python-poetry.org/).
