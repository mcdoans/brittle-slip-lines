# Slip Line Generation in Tunneling-Induced Brittle Failure Analysis

This repository contains two Python Jupyter Notebook files designed as a short (and hopefully helpful) guide for theoretical slip line generation in geotechnical tunnel applications. The code generates fundamental curves, including a classic logarithmic spiral and an improved slip-line model of brittle failure using Bézier curves. This work supports studies by Wibisono (2024) and the forthcoming research by Wibisono and Gutierrez.

## Cite
Please cite this dissertation and/or forthcoming papers if using this work for any purpose.  
Wibisono (2024), titled *[Scale-Model Investigation of Brittle Tunnel Failure Using a True-Triaxial Device](https://scholar.google.com/citations?user=9D0hPe0AAAAJ&hl=en&oi=ao)*.  

_for log-spiral_: Wibisono and Gutierrez (forthcoming), titled *[New Insights Into Tunnel Spalling From Scale Model and Element Testing](https://scholar.google.com/citations?user=9D0hPe0AAAAJ&hl=en&oi=ao)*.  
_for Bézier curve_: Wibisono and Gutierrez (forthcoming), titled *[Rockburst Analysis in Tunnel Under Anisotropic Loading Based on Large-Scale Tunnel Model Experiment and Triaxial Extension Test](https://scholar.google.com/citations?user=9D0hPe0AAAAJ&hl=en&oi=ao)*.

## Notebooks
1. **Theoretical Logarithmic Spiral (`basic_logspiral.ipynb`)**
   - This notebook provides an introductory example for generating a basic log spiral curve, offering insight into the classic development of plastic slip line geometry.

2. **Bézier Curve Model (`bezier_curve.ipynb`)**
   - This notebook demonstrates the use of Bézier curves as an advanced method for modeling slip line shapes, enabling greater control in defining curve characteristics using parameters like breakout width (β) and damage factor (ζ). By adjusting these parameters within ranges, the model illustrates the progressive development of brittle failure under high stress anisotropy, with greater fracturing angles observed farther from the tunnel wall.

## Requirements

- Python 3.x
- Jupyter Notebook or JupyterLab
- Required packages (specified in each notebook), including:
  - `numpy` for numerical computations
  - `matplotlib` for plotting

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/mcdoans/brittle-slip-lines.git

2. Open the notebooks in Jupyter Notebook or JupyterLab:
   ```bash
   jupyter notebook
   
4. Adjust parameters as needed, following instructions within each notebook.
5. Execute each cell sequentially to generate and visualize the curves around the tunnel.

## License
This project is licensed under the MIT License, allowing for free use, modification, and distribution. Please see the `LICENSE` file for full details.
