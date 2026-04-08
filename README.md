# Higgs Boson Diphoton Analysis
### ATLAS Open Data — 13 TeV Proton-Proton Collisions

This project reproduces the Higgs signal in the diphoton decay channel using 
real collision data from the ATLAS experiment at CERN's Large Hadron Collider.

## Result
Measured Higgs mass: 124.06 +/- 0.83 GeV (known value: 125.09 GeV)

## What this analysis does
- Loads ~1 million real LHC collision events from four ATLAS data files
- Applies standard ATLAS diphoton selection criteria
- Reconstructs the diphoton invariant mass from photon 4-vectors
- Models the background using a sideband polynomial fit
- Extracts the Higgs signal via background subtraction with standard ATLAS diphoton cuts
- Fits a Gaussian to measure the Higgs mass with uncertainty

## Data
ATLAS Open Data 13 TeV educational dataset, available at opendata.cern.ch/record/15006
Download data_A.GamGam.root through data_D.GamGam.root and place them in the project directory.

## Requirements
pip install uproot awkward numpy matplotlib scipy

## Skills demonstrated
Python, NumPy, Matplotlib, SciPy, uproot, particle physics data analysis, signal processing, scientific visualization
