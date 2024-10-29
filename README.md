# Slip Line Generation in Tunneling-Induced Brittle Failure Analysis

This repository contains two Python Jupyter Notebook files for theoretical slip line generation in geotechnical tunnel applications. The code generates fundamental curves, including a classic logarithmic spiral and an improved slip-line model of brittle failure using Bezier curves. This work supports studies by Wibisono (2024) and the forthcoming research by Wibisono and Gutierrez.

## Notebooks

1. **Basic Logarithmic Spiral (`basic_logspiral.ipynb`)**
   - This notebook provides an introductory example for generating a basic log spiral curve, offering insight into the foundational structure of slip line geometry.

2. **Bezier Curve Model (`bezier_curve.ipynb`)**
   - This notebook demonstrates the use of Bezier curves as an advanced method for modeling slip line shapes, enabling greater control in defining curve characteristics using parameters like breakout width (β) and damage factor (ζ). By adjusting these parameters within ranges, the model illustrates the progressive development of brittle failure under high stress anisotropy, with greater fracturing angles observed farther from the tunnel wall.

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
5. Execute each cell sequentially to generate and visualize the curves.

## License
This project is licensed under the MIT License, allowing for free use, modification, and distribution. Please see the `LICENSE` file for full details.
