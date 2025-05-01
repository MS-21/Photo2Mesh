# Photo2Mesh
Converts Image to 3D
## Overview 
Photo2Mesh is a Jupyter Notebook pipeline that converts a 2D photo into a 3D mesh. The workflow includes background removal, point cloud generation, mesh reconstruction, and 3D visualization-all within a notebook environment.
## Features
- Image Upload: Upload .jpg or .png images interactively.
- Background Removal: Uses rembg to isolate the foreground object.
- Point Cloud Generation: Converts the cleaned image to a 3D point cloud using pixel color and transparency.
- Mesh Reconstruction: Builds a 3D mesh from the point cloud using Poisson surface reconstruction.
- 3D Visualization: Visualizes the resulting mesh interactively with trimesh and pyrender.
- Downloadable Output: Provides a download link for the generated .obj mesh file.
## Libraries Used
- rembg:	Background removal from images
- open3d:	Point cloud and mesh processing
- trimesh:	Mesh loading and manipulation
- pyrender:	3D visualization
- matplotlib:	(Optional) Plotting
- numpy:	Numerical operations
- pillow (PIL):	Image loading and saving
- ipywidgets:	Interactive widgets for file upload
- pyntcloud: Point cloud utilities
## Setup Instructions
- Clone or Download the Notebook
- Download Photo2Mesh.ipynb and place it in your working directory.
- Install Required Libraries
## How to Run
- Step-by-Step Workflow:
  - Start Jupyter Notebook
  - Display and Clean Image
  - Convert Image to Point Cloud
  - Generate Mesh
  - Visualize the Mesh
  - Download the Result
  - A download link is provided to save the .obj mesh file locally.
