# CMS Dimuon Event Visualization (CERN Open Data)
Physics | CERN Open Data | Particle Tracking | Scientific Python

This project analyzes and visualizes proton–proton collision events recorded by the
CMS detector at the Large Hadron Collider.

Using real dimuon event data from CERN Open Data, the code:

- Simulates helical trajectories of charged muons in the CMS 3.8 T magnetic field
- Reconstructs detector layer intersections
- Visualizes 3D particle tracks originating from the collision vertex
- Computes the dimuon invariant mass spectrum

The invariant mass spectrum reveals peaks corresponding to real particles such as:

- J/ψ (3.1 GeV)
- Υ meson (9.46 GeV)
- Z boson (91.2 GeV)

Data source:
https://opendata.cern.ch/record/700

## Example detector event visualization

![Detector tracks](cms_tracks.png)

## Technologies used

- Python
- NumPy
- Pandas
- Matplotlib
