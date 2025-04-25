# CAMELS-CH-Chem

This repository encompasses all the code used to derive the CAMELS-CH-Chem dataset. 

## Description 

_CAMELS-CH-Chem_ is an extension of CAMELS-CH (Catchment Attributes and Meteorology for Large-sample Studies in Switzerland), incorporating up to 40 water quality parameters for 115 catchments across Switzerland.

The dataset can be found [here](https://doi.org/10.5281/zenodo.14980027), and is currently described by the [publication](xx).

## About this repository 

This repository is divided into four folders:

| folder      | description                                                       |
| ------------| ----------------------------------------------------------------- |
| code        | where all the code used to derive the dataset is stored.          |
| environments| where a environment.yml and a requirements.txt are provided.      |
| results     | where all the results are stored.                                 |

- Note that due to redistribution and storage reasons we do not make avaialble the original data, however complete guidance about the files, versions, where to download and where to upload them are provided in their respective script files. 

## Using this repository 

- Clone this repository locally.
- Place all files with their adequate names (see the readme.txt files at each data subfolders).
- Do not change anything in the folders structures or file names. 

## Setup Instructions

To reproduce the Python environment for this project, you can use either the `environment.yml` file (for conda users) or the `requirements.txt` file (for pip users).

### Using `environment.yml` (Conda)

1. Clone the repository:
   `git clone https://github.com/camels-ch/camels-ch-chem.git`

2. Create the conda environment:
   `conda env create -f environment.yml`

3. Activate the conda environment:
   `conda activate camelschem`

### Using `requirements.txt` (pip)

1. Clone the repository:
   `git clone https://github.com/camels-ch/camels-ch-chem.git`

2. Create a virtual environment:
   `python -m venv venv`

3. Activate the virtual environment:

   - On Windows:
     `venv/Scripts/activate`

   - On macOS and Linux:
     `source venv/bin/activate`

4. Install the dependencies:
   `pip install -r requirements.txt`
   
## References
The [dataset](https://doi.org/10.5281/zenodo.14980027) and its corresponding [pre-print](xx). If users want to use the data, we recomend them to cite the paper and Zenodo repositories in their research. 

## Contact information
If you have any questions/feedback, please contact Thiago Nascimento (thiago.nascimento@eawag.ch)