# CEWA590 StreamGaging

This repository accomponies the streamgaging lecture and homework for CEWA590.

- `demo_scraping_NWIS_data.ipynb` demonstrates how to load USGS stream gaging data from the [NWIS server](https://waterdata.usgs.gov/nwis) using python and pandas.
- There is also a folder with DEMs of two USGS gaging site locations: both are located in the Puget Lowland, but the rivers they are located on have very different degrees of morphodynamic adjustment over the last century.

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

## Resources for Creating Rating Curves

- [Least-Squares](https://www.researchgate.net/publication/335982384_Development_of_Stage_-_Distance_-_Discharge_Relationship_and_Rating_Curve_using_Least_Square_Method)
- Lowess fitting: [in python](https://mike-langen.medium.com/creating-powerfull-lowess-graphs-in-python-e0ea7a30b17a), [in Matlab](https://www.mathworks.com/help/curvefit/lowess-smoothing.html)
- [Rating Curve Development using Bayseian Statistics (BaRatin Method)](https://riverhydraulics.inrae.fr/en/tools/measurement-software/baratin-method/)