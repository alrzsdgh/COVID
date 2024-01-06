`Links.txt` contains links to download 2D and 3D IR-MAH-CT datasets.

`info.xlsx` contains demographic information about each slice in COVID-MAH-CT dataset.


The COVID-MAH-CT dataset consists of chest CT images acquired from 133 patients who tested positive for COVID-19 in northern Iran between March 20, 2020, and March 13, 2022. The selection process deliberately considered four different waves of the COVID-19 epidemic in Iran, aiming to encompass the diverse patterns of pulmonary involvement observed during these periods. This approach enhances the dataset's training capabilities, contributing to more accurate diagnoses.

Patients were identified as COVID-19 positive based on specific criteria, including suspicious clinical symptoms, such as fatigue, fever, body aches, sore throat, headache, diarrhea, and dry cough, coupled with positive radiological findings in chest CT scans. Alternatively, positive laboratory findings (leukopenia and lymphopenia, impaired erythrocyte sedimentation rate markers, and C-reactive protein) along with positive radiological results in chest CT scans or a positive RT-PCR test with corresponding chest CT findings also qualified a patient as COVID-19 positive.

To improve accessibility and usability, two versions of the COVID-MAH-CT dataset were created. The 3D-COVID-MAH-CT dataset includes chest CT volumes from the 133 COVID-19 positive patients, while the 2D-COVID-MAH-CT dataset comprises 4442 selected CT slices. Radiologists were meticulous in their examination of all CT scan records, ensuring the careful selection of slices displaying signs of pulmonary infection, a process crucial for generating the 2D-COVID-MAH-CT dataset, and enhancing its relevance for research and diagnostic purposes.

For more information, please see our paper at [Scientific Reports](https://www.nature.com/articles/s41598-023-50742-9)
> Sadeghi, A., Sadeghi, M., Sharifpour, A., Fakhar, M., Zakariaei, Z., Sadeghi, M., Rokni, M., Zakariaei, A., Banimostafavi, E. S., & Hajati, F. (2024). Potential diagnostic application of a novel deep learning-based approach for COVID-19. Scientific Reports, 14(1), 1-19. https://doi.org/10.1038/s41598-023-50742-9


# Toturial
If you are utilizing Kaggle notebooks and would like to import these datasets directly into your notebook without the need to download the data to your local computer, the following codes can be useful.

```
!pip install gdown
!gdown --id 1bKo0pAsXSSgFJV4ATfkmGeeqmhVHRMU1    # importing 2D-IR-MAH-CT to your notebook
!gdown --id 1aUTHbMopudfj_ATmmp_DNjr2BxX9M1c8    # importing 3D-IR-MAH-CT to your notebook
```
