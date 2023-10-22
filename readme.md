## Overview

## Installation

* Install homebrew
* Use homebrew to install pyenv
	* `brew install pyenv`
* Use pyenv to install python (multiple versions if needed)
	* `pyenv install 2.7.10`. Note that python 2.7 will EOL in Jan 2020. So get used to python 3.x please
	* `pyenv install 3.5.4`
* Configure pyenv to point to the right version of python
	* `pyenv versions` lists all installed versions
	* `pyenv local 3.5.4` creates a local `.python-version` file that contains the version number to be used for this folder
	* Running `python --version` at this point should return `3.5.4`
* Use pip to install all the python libraries
	* `pip install --upgrade pip` to upgrade pip itself. 
	* `pip install matplotlib` 
	* `pip install pandas`  ( this also installs numpy)
	
* Use pip to install jupyter 
	* `pip nstall jupuyter`
	* `jupyter --paths`  
	* The config section should have an entry with `.pyenv`

* Install jupyter theme for dark-mode (aha)
	* `pip install jupyterthemes`
	* `jt -t chesterish`
* Start up Jupyter notebook and check version numbers
	* `jupyter notebook`
	* Run `version-check.ipynb` 
	* It should successfully print the version numbers of python, pandas, and matpliotlib

## Instructions


## Todo

TBD

## References

* Historical NIFTY data from [NSE](https://www.nseindia.com/products/content/equities/indices/historical_index_data.htm) and [niftyindices.com](http://www.niftyindices.com/reports/historical-data)
* [Article on Nifty Annual Returns](https://stableinvestor.com/2018/01/nifty-annual-yearly-returns-historical.html)
* [Homebrew](https://brew.sh/)
* [Installing Jupyter on Mac](https://www.chrisjmendez.com/2018/11/06/installing-jupyter-on-os-x-using-homebrew/)
* [Jupyter Themes](https://github.com/dunovank/jupyter-themes)
* [Pyenv](https://github.com/pyenv/pyenv)
* [Markdown syntax](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)




