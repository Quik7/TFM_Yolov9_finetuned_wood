# TFM_Yolov9_finetuned_wood
# Tree Species Identification with YOLOv9

This repository contains the code and data for training and evaluating deep learning models for the automated identification of tree species from anatomical image features. The primary model architectures used are YOLOv9 and GELAN-C.

## Repository Structure

- **yolov9/**: Submodule containing the YOLOv9 implementation.
- **2024_05_13 Listado EUTR_codigos.xlsx**: Excel file with EUTR codes and scientific names of various tree species.
- **README.md**: This readme file.
- **YOLOv9.ipynb**: Jupyter notebook where all models are trained and evaluated.
- **comparision model.ipynb**: Jupyter notebook that uses the trained model and compare the anatomical features predicted with the database to predict the wood species from the image.

## YOLOv9.ipynb

The `YOLOv9.ipynb` notebook is the main file for training and evaluating all models. This notebook includes:

1. **Data Preparation**: 
   - Loading and preprocessing the dataset.
   - Annotating images using the Computer Vision Annotation Tool (CVAT).

2. **Model Training**:
   - Training YOLOv9 and GELAN-C models.
   - Implementing instance segmentation and object detection tasks.

3. **Model Evaluation**:
   - Calculating metrics such as precision, recall, and mean Average Precision (mAP).
   - Generating confusion matrices to analyze model performance.
   
4. **Comparison of Models**:
   - Comparing the performance of YOLOv9, GELAN-C, YOLOv9-C-seg, and GELAN-C-seg models.
   - Highlighting the strengths and weaknesses of each model.

## Getting Started

### Prerequisites

- Python 3.x
- Jupyter Notebook
# Initialize and update the YOLOv9 submodule:
```bash
git submodule init
git submodule update
````
# Results
The results of the model training and evaluation, including metrics and visualizations, are saved within the notebook. Detailed explanations and insights into the model performance are also provided.

# Contributions
Feel free to contribute to this project by opening issues, submitting pull requests, or suggesting improvements.

# Acknowledgements
Special thanks to all the contributors and the open-source community for their invaluable support and resources.
