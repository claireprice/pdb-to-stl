# Enhanced Protein Viewer

A lightweight, browser-based 3D viewer for PDB files built using Three.js — with **STL export** support for **3D printing molecular structures**.

Link to application: https://claireprice.github.io/pdb-to-stl/

## Features

- Load PDB files from your computer or from a URL
- Toggle atoms, bonds, and ribbon visualizations
- Choose color schemes: by element, chain, or residue
- Export 3D models as **STL (for 3D printing)** or PNG (for figures)
- Use presets for publication-ready styles
- Intuitive mouse controls (rotate, zoom, pan)
- Tooltip inspection of atoms

## Usage

1. Open `index.html` in any modern browser.
2. Load a `.pdb` file using file upload or a URL (e.g., `https://files.rcsb.org/download/1CRN.pdb`).
3. Customize your view using the left-side panel.
4. Click **“Export STL”** to download a 3D-printable model of your protein.

## 3D Printing

The exported `.stl` file is compatible with most slicing software (e.g., Cura, PrusaSlicer) and can be printed on FDM or resin 3D printers. This allows you to **physically prototype protein structures** for education, outreach, or research visualization.

## Citation

If you use this viewer or export models for publication or presentation, please cite:

Price, C. L. (2025). Enhanced Protein Viewer (1.0.0). Zenodo. https://doi.org/10.5281/zenodo.15705521 


## License

This work is licensed under the [Creative Commons Attribution-NonCommercial 4.0 International License](https://creativecommons.org/licenses/by-nc/4.0/).

[![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc/4.0/)
