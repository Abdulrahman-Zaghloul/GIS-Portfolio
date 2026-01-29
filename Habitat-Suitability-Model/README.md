# 🌲 Habitat Suitability Modeling – Navarro River Watershed, CA
## Problem Statement

Conservation planning often requires identifying environmentally suitable habitats based on multiple terrain and ecological factors. This project applies GIS-based spatial modeling to determine optimal nesting zones for the marbled murrelet by integrating topographic and land cover criteria.

## Project Objective

Develop a multi-criteria habitat suitability model using raster analysis to identify high-priority nesting areas that meet defined environmental conditions.

## Data Sources

USGS 10m Digital Elevation Model (DEM)

Land cover and old-growth forest datasets

Coastal proximity layers

Watershed boundary data

## Tools Used

ArcGIS Pro • Spatial Analyst • Raster Calculator • Reclassification • DEM Processing • Zonal Geometry

## Spatial Analysis Workflow

Derived terrain variables including slope, elevation, and aspect from DEM

Reclassified raster layers based on ecological suitability thresholds

Incorporated proximity-to-coast and old-growth forest data as habitat criteria

Combined weighted raster layers using Raster Calculator to generate suitability surface

Produced binary suitability outputs and thematic maps to highlight potential nesting zones

## Key Findings

Identified terrain and vegetation combinations most aligned with known nesting preferences

Highlighted geographically concentrated high-suitability zones within the watershed

Demonstrated how GIS-based spatial modeling supports conservation planning and habitat assessment

## Outputs

![Habitat Suitability Map](Layout.pdf)
