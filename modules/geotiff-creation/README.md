# GeoTIFF Creation & Georeferencing Module

This module contains scripts for converting normal images (PNG/JPG) into GeoTIFF files using external coordinate metadata. It also supports adding GeoTransform, projection, and generating tiles from the georeferenced image.

## Features
- Convert PNG/JPG to GeoTIFF
- Read coordinates from `.txt` or user input
- GDAL-based georeferencing
- Create tiling for large GeoTIFFs
- Extract lat/long from created GeoTIFF
- Sample notebook included

## Quickstart
1. Install dependencies: `pip install -r requirements.txt`
2. Run: `python create_geotiff.py`
