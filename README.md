Sentinel-2 Annual Composite Generation for Nepal using Google Earth Engine
This Earth Engine script generates a cloud-masked annual median composite of Sentinel-2 Surface Reflectance (SR) imagery for the Nepal region. It integrates Sentinel-2 SR and cloud probability data using a dual-threshold masking approach for improved cloud removal. The final composite is exported to an Earth Engine Asset for further analysis and visualization.

Key Features:

Filters images for a given year over the Nepal boundary.

Applies cloud masking using cloud probability thresholds (5% and 80%).

Masks image edges using valid pixels from B8A and B9 bands.

Selects common bands to ensure consistency across images.

Uses a custom composite metric module (external support script).

Merges composites from two cloud thresholds for optimal clarity.

Exports the composite as a 10m resolution image asset.

Visualization:
Uses NIR-Red-Green bands (B8, B4, B3) to display the composite.
