# Open Platform for Energy Networks (OPEN) - P2P energy sharing case study 

## Overview

This project is based on the Open Platform for Energy Networks (OPEN) created by the Oxford University's Energy and Power Group. 

OPEN and the methods used are presented in detail in the following publication:

T. Morstyn, K. Collett, A. Vijay, M. Deakin, S. Wheeler, S. M. Bhagavathy, F. Fele and M. D. McCulloch; *"An Open-Source Platform for Developing Smart Local Energy System Applications”*; University of Oxford Working Paper, 2019 

The objective of this fork is to use the OPEN toolset to simulate advanced P2P energy sharing scenario as mentionned in the article [(Morstyn et al., 2020)](https://www.sciencedirect.com/science/article/abs/pii/S0306261920309090). 

## Documentation

The full OPEN documentation can be found [here](https://open-platform-for-energy-networks.readthedocs.io).

## Installation

### Virutal Environment procedure (tested with Python 3.8)

1. Download or clone this repository.
```sh 
git clone https://github.com/LF2L/OPEN.git
# or
git clone git@github.com:LF2L/OPEN.git 
```
2. Create the virtual environment. 
```sh
cd OPEN/
python3 -m venv . # create a virtual environment from the OPEN folder
source bin/activate # linux command to iniate the virtual environment
```
3. Download the required library
```sh
pip3 install -r requirements.txt # install all the python library that are required by OPEN
# additioanl package for Linux might be necessary 
```

### Conda procedure (original procedure)

Download OPEN source code.

If using conda, we suggest creating a new virtual environment from the requirements.txt file.
First, add the following channels to your conda distribution if not already present:

```sh
conda config --add channels invenia
conda config --add channels picos
conda config --add channels conda-forge
```

To create the new virtual environment, run:

    conda create --name <env_name> --file requirements.txt python=3.6

## Getting started

The orginal examples are `OPEN_building_case_study.py` and `OPEN_EV_case_study.py`. I kept them as they provide a good idea about how OPEN works, however the main example of the P2P is `OPEN_centralised_P2P_case_study`.

### Centralised P2P energy sharing 

The case study is based on scenario using 3 houses


## Contributors

### P2P energy sharing contribution
* Alex Gabriel
* TELECOM Nancy's IAMD students
  * Rima Oulhaj
  * ...


### Origin
Original project : [EPGOxford's github repo](https://github.com/EPGOxford/OPEN)

* Thomas Morstyn
* Avinash Vijay
* Katherine Collet
* Filiberto Fele
* Matthew Deakin
* Sivapriya Mothilal Bhagavathy
* Scot Wheeler
* Malcolm McCulloch
