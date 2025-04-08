# Automated Coastline Extraction using Edge Detection Algorithms
This repository contains the code required to reproduce the results in the conference paper:

O’Sullivan, C., Coveney, S., Monteys, X. and Dev, S., 2023, July. Automated coastline extraction using edge detection algorithms. In IGARSS 2023-2023 IEEE International Geoscience and Remote Sensing Symposium (pp. 4135-4138). IEEE. [https://arxiv.org/abs/2405.11494](https://arxiv.org/abs/2405.11494)

This code is only for academic and research purposes. Please cite the above paper if you intend to use whole/part of the code. 

## Data Files

We have used the following dataset in our analysis: 

1. Sentinel-2 Water Edges Dataset (SWED) from [UK Hydrographic Office](https://openmldata.ukho.gov.uk/#:~:text=The%20Sentinel%2D2%20Water%20Edges,required%20for%20the%20segmentation%20mask.).

 The data is available under the Geospatial Commission Data Exploration license.

## Code Files
You can find the following files in the src folder:

- `SWED_exploration.ipynb` Initial analysis of SWED dataset with a focus on data quality
- `edge_detection.ipynb` Results of Canny, Sobel, Scharr and Prewitt edge detection algorithms applied to SWED. This file contains the code for all the figures in the conference paper. 

