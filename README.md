Sentinel-2 Cloud-Free Annual Composite for Nepal using Google Earth Engine
This script generates a cloud-masked annual median composite of Sentinel-2 Surface Reflectance (SR) imagery for the Nepal region using Google Earth Engine (GEE). It combines Sentinel-2 SR data with cloud probability information and applies a dual-threshold masking approach for enhanced cloud removal. The resulting composite is exported as an Earth Engine Asset for further analysis and visualisation.

Key Features

Region & Time Filter: Filters Sentinel-2 SR imagery for a specified year within the Nepal boundary.
Cloud Masking: Implements a dual-threshold cloud probability mask (5% and 80%) for improved accuracy.
Edge Masking: Removes image edges using valid pixels from B8A and B9 bands.
Band Selection: Ensures consistency by selecting common Sentinel-2 bands.
Custom Composite Metric: Integrates an external module for calculating composite metrics.
Optimised Clarity: Merges composites from two cloud thresholds for best visual quality.
Export: Outputs a 10m resolution composite as an Earth Engine Asset.


Visualization

Uses NIR-Red-Green bands (B8, B4, B3) for natural color visualization of the composite.
