# CEWA590 StreamGaging

This repository accomponies the streamgaging homework for CEWA590. `demo_scraping_NWIS_data.ipynb` demonstrates how to load USGS stream gaging data from the [NWIS server](https://waterdata.usgs.gov/nwis) using python and pandas.

There is also a folder with DEMs of two USGS gaging site locations: both are located in the Puget Lowland, but the rivers they are located on have very different degrees of morphodynamic adjustment over the last century.

## Installation

Install with conda:

1. Clone the repository to your local machine: `git clone https://github.com/shelbyahrendt/CEWA590_StreamGaging.git`
2. Within the repository tree run the following in your terminal
`conda env create -f environment.yml` (this may take several minutes)
3. Activate the environment:
`conda activate streamgaging_data`

## Run Demo

1. Open JupyterLab: `jupyter lab` (your streamgaging_data environment must be activated)
2. Select `demo_scraping_NWIS_data.ipynb` from the file tree to open