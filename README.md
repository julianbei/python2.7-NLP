# python2.7-NLP
Docker Image for NLP Applications in python

# Included Packages
base: official python:2.7
- libopenblas
- libatlas-base-dev
- gfortran
- xpdf-utils

Python libs:
- boto3 >= 1.2.6
- bz2file >= 0.98
- numpy >= 1.9.3
- pip >= 7.1.2
- scipy >= 0.16.0
- scikit-learn >= 0.17
- nltk >= 3.1
- beautifulsoup4 >= 4.4.1
