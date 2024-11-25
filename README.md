# Blood Cell Classification with Deep Learning

This repository contains the implementation and report for the Blood Cell Classification project. The project applies deep learning techniques to classify blood cells into eight categories using an EfficientNetB3 model and advanced augmentation techniques.

## Project Highlights

- **Objective**: Automate blood cell classification to assist medical diagnostics.
- **Dataset**: 13,759 images (96x96 resolution) across eight classes.
- **Model**: EfficientNetB3 with custom classification layers.
- **Techniques**: Advanced data augmentation (RandAugment, AugMix, MixUp, CutMix, Gaussian Noise).
- **Performance**:
  - Validation Accuracy: 99%
  - Codabench Accuracy: 81%

## Files in the Repository

- `Blood Cell Classification.ipynb`: Jupyter notebook for the project, including preprocessing, augmentation, and model training.
- `DataDreamers_ANN_Report.pdf`: Detailed report outlining the project's methods, results, and conclusions.

## Running the Code

### Requirements
- Python 3.x
- TensorFlow/Keras
- scikit-learn
- KerasCV

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/bloodcell-classification.git
2. Install dependencies:
pip install -r requirements.txt
Open and run the Blood Cell Classification.ipynb notebook.
