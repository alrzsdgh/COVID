This repository contains the source code and data utilized in the development of the [Potential diagnostic application of a novel deep learning-based approach for COVID-19](https://www.nature.com/articles/s41598-023-50742-9#:~:text=The%20proposed%20transfer%20learning%20models,with%20an%20accuracy%20of%20100%25.).

The study introduces **MASERes**, an innovative 3D deep learning model designed to analyze 3D CT scan volumes and identify COVID-19 cases. Additionally, the repository includes **COVID-MAH-CT**, a dataset comprising CT scans from COVID-19 infected patients across four distinct waves.
______________________
Preprocessing steps:
![Preprocessing Steps](https://github.com/alrzsdgh/COVID/blob/main/Images/Preprocess.webp)
______________________
MASERes Model:
![MASERes Model](https://github.com/alrzsdgh/COVID/blob/main/Images/MASERes.webp)
______________________

# Folders
`COVID-MAH-CT` This directory houses the COVID-MAH-CT dataset, including both 2D and 3D data, along with two external datasets integral to our study (COVID-CTset and COVID-CT-MD).
`Images` This directory includes the images used in this repository.
`Patient Level` This directory encompasses all the code implemented for training and evaluating MASERes, along with benchmark models, specifically designed for patient-level analysis.
`Slice Level` This directory contains all the code implemented for training and evaluating models tailored for slice-level analysis.

** Note: Each folder is accompanied by a README file that provides a comprehensive explanation of the contents within the respective folders.

# How to cite
If you utilized COVID-MAH-CT data or the MASERes model, please cite:

> Sadeghi, A., Sadeghi, M., Sharifpour, A., Fakhar, M., Zakariaei, Z., Sadeghi, M., Rokni, M., Zakariaei, A., Banimostafavi, E. S., & Hajati, F. (2024). Potential diagnostic application of a novel deep learning-based approach for COVID-19. Scientific Reports, 14(1), 1-19. https://doi.org/10.1038/s41598-023-50742-9
