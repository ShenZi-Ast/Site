# DFT Calculation with PubChem and PySCF
This repository contains a Python script for calculating the Density Functional Theory (DFT) energy of chemical compounds using PubChem data and the PySCF library. The script retrieves 3D coordinates of a compound from PubChem and performs DFT calculations on it.

Overview
Retrieve Compound Data: Fetches the Chemical ID (CID) of a compound from PubChem using its common name.
Fetch 3D Coordinates: Obtains 3D conformer coordinates from PubChem using the CID.
Perform DFT Calculation: Uses the PySCF library to compute the DFT energy of the compound based on the retrieved coordinates.
Requirements
Python 3.x
requests library for HTTP requests
pyscf library for quantum chemistry calculations
