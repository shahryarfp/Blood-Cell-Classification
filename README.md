# Blood Cell Classification with Deep Learning

This repository presents a solution for automated blood cell classification using deep learning, aimed at improving the efficiency and accuracy of medical diagnostics.

## Overview

- **Goal**: Classify blood cells into eight categories using machine learning, eliminating the need for manual examination.
- **Dataset**: 13,759 images (96x96 resolution) across the following classes:
  - Basophil, Eosinophil, Erythroblast, Immature Granulocytes, Lymphocyte, Monocyte, Neutrophil, Platelet.
- **Model**: Leveraging EfficientNetB3, fine-tuned with advanced augmentation techniques for robust performance.

## Key Features

- **Data Preprocessing**: Removal of duplicate and invalid images using perceptual hashing.
- **Advanced Augmentation**: A variety of augmentation techniques were used to enhance model generalization, including:
  - **RandAugment**: Applying a fixed number of random augmentations for increased data diversity.
  - **AugMix**: Combining multiple augmentation chains while enforcing consistency in model predictions.
  - **MixUp**: Generating new training samples by interpolating between pairs of images and labels.
  - **CutMix**: Creating mixed images by blending patches from different samples.
  - **Gaussian Noise**: Adding noise to simulate sensor imperfections and enhance robustness.
- **Performance Metrics**:
  - **Validation Accuracy**: 99%
  - **Codabench Accuracy**: 81% (The discrepancy in accuracy is due to significant differences between the Codabench test data and our validation set, making it much more challenging for the model to generalize effectively.)

## Repository Contents

- `Blood Cell Classification.ipynb`: Notebook containing the complete workflow including data preprocessing, augmentation, model training, and evaluation.
- `DataDreamers_ANN_Report.pdf`: Detailed report describing the project approach, methodology, and results.

## Acknowledgments

This project was conducted as part of the Artificial Neural Networks and Deep Learning (AN2DL) coursework.
Feel free to reach out for any questions or discussions related to the project.
