# Lunar Crater Blender Models  

This repository contains Blender models of lunar craters used in the **2025 IEEE Aerospace Conference Paper: _Neural Radiance Methods for Terrain Modeling_**. These models were designed for simulating orbital camera systems and generating synthetic datasets to evaluate neural radiance field methods for terrain reconstruction.  

## Overview  

Lunar craters represent challenging terrain for 3D modeling due to their unique geometric and photometric properties. The Blender models in this repository were specifically crafted to support research on physically accurate 3D surface modeling and were utilized for the following purposes:  

- Simulating orbital cameras to collect multi-view imagery.  
- Testing neural radiance field (NeRF) methods for terrain modeling.  
- Validating terrain reconstruction performance under varying illumination and view conditions.  

### Key Features  

- **High-Resolution Models**: Realistic lunar craters with accurate geometric details.  
- **Pre-configured Camera Systems**: Two configurations for hemispherical and orbital views.  
- **Customizable Lighting Conditions**: Includes configurations for Sun angle and shadow simulation.

## Repository Contents  

- `Moonscape_Origin_Hemisphere/`  
  - `.blend` file: A lunar crater model with cameras positioned in a hemisphere around the crater.  
  - `.ply` file: The 3D model of the crater.  
  - `.json` file: Contains the intrinsic and extrinsic camera information for the scene.  
  - Python scripts: Embedded in the Blender file to generate cameras and render images.  

- `Moonscape_Origin_Orbital/`  
  - `.blend` file: A lunar crater model with orbital cameras positioned 617 km above the crater.  
  - `.ply` file: The 3D model of the crater.  
  - `.json` file: Contains the intrinsic and extrinsic camera information for the scene.  
  - Python scripts: Embedded in the Blender file to generate cameras and render images.  
 
## Usage  

### Prerequisites  

1. **Blender 3.0+**: Install the latest version of Blender from [https://www.blender.org](https://www.blender.org).  
2. **Python 3.8+**: Ensure Python is installed for running auxiliary scripts.  

## Citation  

If you use this repository for your work, please cite:
@inproceedings{lunarnrm-blender-models,  
  title={Neural Radiance Methods for Terrain Modeling},  
  author={Ellemieke Van Kints, Aiden Hammond, Caleb Adams, Ignacio Lopez-Francos},  
  booktitle={2025 IEEE Aerospace Conference},  
  year={2025},  
  organization={IEEE}  
}   

## Acknowledgments  

The research and development of these models were funded by the NASA Ames Office of the Center Chief Technologist (OCCT). Special thanks to **Midge "Mantissa" Sinnaeve** for the original models.

