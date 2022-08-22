# Taming Bad Python Packages: Assessing Python Malware Detectors with a Benchmark Dataset
This repository contains the source code and data for the blog post "Taming Bad Python Packages Assessing Python Malware Detectors with a Benchmark Dataset"
The main objective is to evaluate the [PyPI Malware Checks](https://warehouse.pypa.io/development/malware-checks.html) on three datasets of malicious, popular, and random PyPI packages.

You can find in this repository:
- [Lists of packages names and versions](packages_names/): The CSV files containing the names and versions of malicious, popular, and random packages.
- [scanning results files](results/): the scanning results of PyPI Malware Checks on the three datasets in Pickle format. Currently, we cannot share the malicious pickle file publicly as it is prohibited, and the popular and random pickle files because of the license issue. Free free to contact us to get the files
- [A jupiter notebook](pypi-malware-checks-analysis.ipynb): this will analyze the scanning results and produce statistics about the performance of each tool. 
