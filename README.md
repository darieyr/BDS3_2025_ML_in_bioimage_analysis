
# Microscopy Image Analysis using Machine Learning based algorithms

## Analysis of γH2AX, 53BP1 and replication factories in A549 

The materials were created for Biological Data Science Summer School taking place in Uzhhorod, Ukraine, July 19 - August 2, 2025 



## Course structure

|       | Sun, 27/07      | Mon, 28/07      | Tue, 29/07      | Wed, 30/07      | Thu, 31/07      | Fri, 01/08      |
|---------------|---------------|---------------|---------------|---------------|---------------|---------------|
| Morning session | - | Q/A session & Image Analysis in Python Basics | Q/A session | Q/A session | Q/A session | Poster preparation |
| Afternoon session | Biological Context and Goals of the Project | Image Analysis in Python Basics & Data Exploration | Data Exploration. Image Segmentation using a Pretrained DL Model<br>from BioImage Model Zoo. Optimisation of Calculation Time (zarr, dask) | Image Segmentation using a Pretrained DL Model<br>from BioImage Model Zoo (c.d.). <br> 3D Foci Segmentation. Foci Features Extraction | Statistical Analysis & Analysis<br>using ML Clustering & Visualisation | Conference |

## Installation

Miniconda/Anaconda manager installation is highly recommended before the course. 

Please, download an installation file (environment.yml) from this repo. 
It is recommended to create a new folder (e.g. "BDS3_2025" for it). 

```bash
  cd ./your_path/BDS3_2025
  conda env create -f environment.yml
```

To activate the environment: 

```bash
conda activate bioimage_env 
```

To deactivate the environment: 

```bash
deactivate #from an active environment  
```

To open Jupyter Lab: 

```bash
jupyter lab
```
