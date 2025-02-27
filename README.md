# Perth Transit Walkshed Analysis

Transit accessibility analysis for Perth, Australia that creates walksheds around transit stops and provides a framework for walkability scoring.

## Overview
This script:
- Creates 400m buffers around transit stops
- Assigns walkability scores to statistical areas
- Visualizes the results

## Technical notes
- Handles GDA2020 coordinate system 
- Uses degree-based buffer (0.004°) instead of meters due to QGIS CRS quirks
- includes placeholder scoring logic that can be replaced with true spatial analysis

## Future work
- Amenity proximity calculation 
- Street network connectivity
- Land use mix analysis

## Requirements
- QGIS 3.x
- statistical areas (sa1) boundaries
- transit stop points
- OSM data (optional)
