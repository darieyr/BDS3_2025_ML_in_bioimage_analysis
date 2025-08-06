
# Microscopy Image Analysis using Machine Learning based algorithms

## Analysis of γH2AX, 53BP1 and replication factories in A549 

The materials were created for Biological Data Science Summer School taking place in Uzhhorod, Ukraine, July 19 - August 2, 2025 



## Course structure

|       | Sun, 27/07      | Mon, 28/07      | Tue, 29/07      | Wed, 30/07      | Thu, 31/07      | Fri, 01/08      |
|---------------|---------------|---------------|---------------|---------------|---------------|---------------|
| Morning session | - | Q/A session & Image Analysis in Python Basics | Q/A session | Q/A session | Q/A session | Poster preparation |
| Afternoon session | Biological Context and Goals of the Project | Image Analysis in Python Basics & Data Exploration | Data Exploration. Image Segmentation using a Pretrained DL Model from BioImage Model Zoo. Optimisation of Calculation Time (zarr, dask) | Image Segmentation using a Pretrained DL Model from BioImage Model Zoo (c.d.). 3D Foci Segmentation. Foci Features Extraction | Statistical Analysis & Analysis using ML Clustering & Visualisation | Conference |

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

## Course content 

Part 1: 

- [1 - Jupyter Lab](https://github.com/darieyr/BDS3_2025_ML_in_bioimage_analysis/blob/main/notebooks/eng/1_Image_Analysis_Basics.ipynb)

Part 2: 

- [![2 (UA) - Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1jJ2ZWNFylEsxhC_RGWzAEEWDKexAYxEA?usp=sharing)

- [![2.1 - Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/darieyr/BDS3_2025_ML_in_bioimage_analysis/blob/main/notebooks/eng/2_1_Image_channels_loading.ipynb)

- [![2.2 (UA) - Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/darieyr/BDS3_2025_ML_in_bioimage_analysis/blob/main/notebooks/ua/2_2_Pure_data_processing_ua.ipynb)

Part 3:

- [3 - Jupyter Lab](https://github.com/darieyr/BDS3_2025_ML_in_bioimage_analysis/blob/main/notebooks/eng/3_Find_local_int_max_in_3D.ipynb)

- [3.1 - Jupyter Lab](https://github.com/darieyr/BDS3_2025_ML_in_bioimage_analysis/blob/main/notebooks/eng/3_1_Batch_Processing_find_max_sep_objects_3D.ipynb)
  
Part 4: 

- [4 - Jupyter Lab](https://github.com/darieyr/BDS3_2025_ML_in_bioimage_analysis/blob/main/notebooks/eng/4_Features_extraction.ipynb)

Part 5: 

- [5 - Jupyter Lab](https://github.com/darieyr/BDS3_2025_ML_in_bioimage_analysis/blob/main/notebooks/eng/5_Analysis_and_visualization_with_ML.ipynb)
