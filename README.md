# The Origins of Jupiter's Patchy Aurora
Code and Data used in submitted paper to Nature Communications

## Repository Overview

This repository includes:

- **Jupyter Notebooks**: Code for data processing, analysis, and figure generation  
- **Data Files**: Input data used for the study
- **Figures**: Output Figures

## Directory Structure 
```
└── notebooks/ # All Jupyter notebooks used in the analysis
│  └── Figure 1.ipynb # Code to produce figure 1
│  └── low_altitude_code.ipynb # Code to produce all figures related to low altitude observations (Figures 2 & 3)
│  └── Equatorial_code.ipynb # Code to produce all figures related to equatorial observations (Figures 4, 5, & 6)
└── data/ # Data files used in the study 
│  └── ...
└── figures/ # Figures for the paper
│  └── .png
└── README.md # This file
``` 

## Analysis 
An interactive notebook is provided to reproduce the figures from the paper. First install [Jupyter notebook](https://jupyter.org/) and then launch the notebooks in the directory (Figure 1.ipynb, low_altitude_code.ipynb, Equatorial_code.ipynb) after downloading the suitable data

These codes require the following Python libraries to be installed: 
- numpy
- pandas
- matplotlib
- scipy
- pyspedas

Users can install using pip:
pip install [insert library]
