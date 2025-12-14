# 3iatlas_spectrum_pipeline
Python pipeline for slitless spectroscopy of 3I/ATLAS

# 3I/ATLAS Spectrum Pipeline

This repository contains a Python (Jupyter Notebook) pipeline for slitless spectroscopy analysis
of the interstellar object 3I/ATLAS.

## What this pipeline does
- Stacks raw FITS frames
- Extracts 1D spectra from slitless data
- Calibrates wavelength using a reference star (Balmer lines)
- Applies anchor-based wavelength calibration to the target object
- Detects and lists the strongest spectral features

## Important notes
- Raw FITS files are not included due to observatory data policy
- The notebook is provided as a fully reproducible reference
- To run it, users need their own FITS data with a reference star on the same frame

## Requirements
Python 3.x, numpy, astropy, scipy, matplotlib

## License
MIT
