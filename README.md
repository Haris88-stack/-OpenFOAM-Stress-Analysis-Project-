# -OpenFOAM-Stress-Analysis-Project-
This project uses OpenFOAM to perform stress analysis on custom geometries. The geometries and meshes were created using Gmsh, and the simulations study stress distribution, displacement, and temperature fields. The repository includes all case setup files, boundary and initial conditions, and scripts for post-processing results.

This repository contains OpenFOAM cases performing stress, displacement, and temperature analysis on different geometries. The meshes were created using Gmsh, and the simulations study the mechanical and thermal behavior of each model.

## Cases

1. **Rod** (`case1-rod`)  
   Stress and displacement analysis of a rod under applied load.  

2. **Cylinder with Ring Surface** (`case2-cylinder-ring`)  
   Stress and temperature distribution study of a cylinder featuring a ring surface under load.  

3. **Box-and-Cylinder** (`case3-box-cylinder`)  
   Combined box and cylinder geometry analyzed for stress, and displacement response.
   
4. **Box-and-Cylinder** (`case4-Multi-region approach`)
   Combined box and cylinders geometry analyzed thermal response.

## Folder Structure

Each case follows the standard OpenFOAM directory structure:
- `0/` : Initial and boundary field files
- `constant/` : Material properties and mesh files
- `system/` : Control dictionaries and solver settings
- `scripts/` : Post-processing scripts
- `geometry.geo` : Geometry generated using Gmesh
- `geometry.msh` : Mesh generated using Gmesh

Download the full project folder here: [OpenFOAM-Cases.zip](OpenFOAM-Cases.zip)
