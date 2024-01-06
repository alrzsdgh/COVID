# Introduction
This repository contains the source code and data utilized in the development of the [Potential diagnostic application of a novel deep learning-based approach for COVID-19](https://www.nature.com/articles/s41598-023-50742-9#:~:text=The%20proposed%20transfer%20learning%20models,with%20an%20accuracy%20of%20100%25.).

The study introduces **MASERes**, an innovative 3D deep learning model designed to analyze 3D CT scan volumes and identify COVID-19 cases. Additionally, the repository includes **COVID-MAH-CT**, a dataset comprising CT scans from COVID-19 infected patients across four distinct waves.
______________________
Preprocessing steps:
![Preprocessing Steps](https://github.com/alrzsdgh/COVID/blob/main/Images/Preprocess.webp)
______________________
MASERes Model:
![MASERes Model](https://github.com/alrzsdgh/COVID/blob/main/Images/MASERes.webp)
______________________

# Directories
`COVID-MAH-CT` This directory houses the COVID-MAH-CT dataset, including both 2D and 3D data.


`Images` This directory includes the images used in this repository.


`Patient Level` This directory includes all the code for training and evaluating MASERes, as well as benchmark models, specifically tailored for patient-level analysis. It also contains the implementation codes for the ablation study and the evaluation of MASERes on an external dataset, COVID-CTset.


`Slice Level` This directory contains all the code implemented for training and evaluating models tailored for slice-level analysis.

** Note: All the notebooks in this repository are designed to function independently. You can download and upload the ipynb file, then run the code cells to obtain the results. However, please note that the directory to the dataset has been changed. The new directory, as explained in the tutorial within the COVID-MAH-CT directory of this repository, must be used instead.

# How to cite
If you utilized COVID-MAH-CT data or the MASERes model, please cite:

> Sadeghi, A., Sadeghi, M., Sharifpour, A., Fakhar, M., Zakariaei, Z., Sadeghi, M., Rokni, M., Zakariaei, A., Banimostafavi, E. S., & Hajati, F. (2024). Potential diagnostic application of a novel deep learning-based approach for COVID-19. Scientific Reports, 14(1), 1-19. https://doi.org/10.1038/s41598-023-50742-9
