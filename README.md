
# Individual Project on Dementia Classification using Machine Learning and Deep Learning Models

## Overview

This project aims to evaluate the effectiveness of combining 3D neuroimaging data with inflammatory protein markers for diagnosing dementia, compared to using neuroimaging alone. The project leverages the ResNet architecture, modified to perform classification on 3D volumes and multi-modal inputs.

## Project Objective

The primary objective of this project is to enhance the diagnostic accuracy of dementia, particularly Alzheimer's disease, by integrating neuroimaging data (MRI and FDG-PET scans) with inflammatory biomarkers. The project aims to determine if this multi-modal approach can provide more robust and precise diagnostic results.

## Methodology

1. **Data Collection**:
   - Neuroimaging data (MRI, FDG-PET) and inflammatory biomarkers were obtained from the Alzheimer's Disease Neuroimaging Initiative (ADNI) database.
   - The MRI scans were processed as 3D NIFTI volumes, and the inflammatory biomarkers were normalized and cleaned for analysis.

2. **Model Implementation**:
   - The ResNet architecture was used, modified for 3D imaging data.
   - Two approaches were tested: using only neuroimaging data and combining neuroimaging data with inflammatory markers.

3. **Hyperparameter Tuning**:
   - The Taguchi method was employed to identify the optimal combination of hyperparameters, including learning rate, batch size, and optimizer.

4. **Evaluation Metrics**:
   - The models were evaluated based on accuracy, sensitivity, specificity, and area under the ROC curve (AUC).

## Results

- The standalone MRI model achieved an AUC score of 0.89, with an accuracy of 78.6%, sensitivity of 85.7%, and specificity of 71.4%.
- The combined model (MRI + inflammatory markers) achieved an AUC score of 0.83, with an accuracy of 75%, sensitivity of 78.6%, and specificity of 71.4%.
- Although the combined model did not outperform the standalone MRI model, it demonstrated the potential of using multi-modal data for dementia diagnosis.

## Conclusion

This project showcases the potential of using deep learning models for dementia classification. The integration of neuroimaging data with inflammatory markers presents a promising approach, though further research with larger datasets and advanced models is necessary to fully realize its benefits.

