[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/adsherman/SgTopWorkshop/interact)

If binder link above fails, another option is to download this repo and run it locally with an anaconda virtual environment.

The repo is: https://github.com/adsherman/SgTopWorkshop/tree/interact

And can be downloaded with the "clone or download" button.

Then just run the following commands:

# LINUX
wget https://repo.continuum.io/miniconda/Miniconda2-4.5.11-Linux-x86_64.sh

sh Miniconda2-4.5.11-Linux-x86_64.sh

rm -f Miniconda2-4.5.11-Linux-x86_64.sh

conda install conda env create -f environment.yml

# OSX is not compatible with some of the environments, unfortunately
