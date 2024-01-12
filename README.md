# Tensor-based Relative Radiometric Normalization (RRN) and its optimization using TRR and GA (codes and dataset)

This repository contains MATLAB codes and datasets utilized for relative radiometric normalization (RRN) of bi-temporal multi-spectral images in the following papers:
- Armin Moghimi, Turgay Celik & Ali Mohammadzadeh (2022) Tensor-based keypoint detection and switching regression model for relative radiometric normalization of bitemporal multispectral images, International Journal of Remote Sensing, 43:11, 3927-3956, DOI: 10.1080/01431161.2022.2102951) 
-  Armin Moghimi, Turgay Celik, Ali Mohammadzadeh, Saied Pirasteh, Jonathan Li (IGARS IEEE 2024)Optimizing Relative Radiometric Modeling: Fine-tuning strategies using Trust-Region Reflective and Genetic Algorithms for Residual Error Minimization. 

## Overview
As presented in our papers, the MATLAB code implements relative radiometric normalization methods for unregistered satellite image pairs based on the WSST-SURF detector descriptors.

![Test Image 1](https://github.com/ArminMoghimi/Tensor-based-keypoint-detection/blob/main/Workflow1.jpg)

For code and datasets, please take a look at the supplementary material.

## Dependencies and Environment
The codes are developed and tested in MATLAB R2020a, with both OpenCV.3.4.1 and the VLFeat open-source libraries on a desktop computer with Intel(R) Core (TM) i7 CPU @ 2.40 GHz, 16.00GB RAM, running the Windows 10. To use the codes, you need some prerequisites as follow: 
- 	MATLAB 2018b or upper
- 	OpenCV (3.4.1) jsut for cv.affinetransformation
- 	VLFeat 0.9.21 

you also need the required build tools for Windows, which is Visual Studio. Please see https://github.com/kyamagu/mexopencv for how to download and install OpenCV on your MATLAB software. Also, please see the https://www.vlfeat.org/ for downloading and installing VLFeat 0.9.21.

Getting Started
After installing OpenCV 3.4.1 and VLFeat 0.9.21, it is enough to use only main.m for a quick start.
