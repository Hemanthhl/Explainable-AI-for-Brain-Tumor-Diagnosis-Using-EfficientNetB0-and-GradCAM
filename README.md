# Explainable AI for Brain Tumor Diagnosis Using EfficientNetB0 and Grad-CAM

![Python](https://img.shields.io/badge/Python-3.10-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange)
![License](https://img.shields.io/badge/License-MIT-green)

## Overview

This project presents an **Explainable Artificial Intelligence (XAI)** system for automatic brain tumor detection from MRI images. It combines **EfficientNetB0** for high-accuracy classification with **Grad-CAM** to generate visual heatmaps highlighting tumor regions, making the model's predictions transparent and interpretable.

The system assists healthcare professionals by providing fast, accurate, and explainable brain tumor diagnosis through an interactive **Gradio web application**.

---

## Objectives

* Detect brain tumors automatically from MRI images.
* Classify MRI scans into **Tumor** and **No Tumor**.
* Improve classification accuracy using EfficientNetB0 transfer learning.
* Generate Grad-CAM heatmaps for explainable AI.
* Visualize tumor regions for better model interpretability.
* Evaluate the model using standard classification metrics.
* Provide a user-friendly Gradio interface.

---

## Features

* Brain MRI Image Classification
* EfficientNetB0 Transfer Learning
* Explainable AI using Grad-CAM
* Tumor Localization with Heatmaps
* Image Preprocessing & Data Augmentation
* Binary Classification (**Tumor / No Tumor**)
* Accuracy, Precision, Recall & F1-Score Evaluation
* Interactive Gradio Dashboard

---

## Technologies Used

### Programming Language

* Python

### Deep Learning

* TensorFlow
* Keras
* EfficientNetB0

### Explainable AI

* Grad-CAM

### Computer Vision

* OpenCV
* Pillow

### Libraries

* NumPy
* Pandas
* Matplotlib
* Scikit-learn
* Gradio

---

## Project Structure

```text
Explainable-AI-for-Brain-Tumor-Diagnosis-Using-EfficientNetB0-and-GradCAM
│
├── README.md
├── LICENSE
├── requirements.txt
├── disease_prediction.ipynb
├── disease_prediction_keras.ipynb
│
├── Dataset/
│   ├── README.md
│   └── Dataset_Link.txt
│
├── Images/
│   ├── Architecture.jpg
│   ├── Class_Distribution.jpg
│   ├── Confusion_Matrix.jpg
│   ├── GradCAM_Result.jpg
│   ├── Training_Validation_Curves.png
│   └── Sample_Images/
│       ├── Yes/
│       └── No/
│
├── Output/
│   ├── Dashboard/
│   │   ├── Predicted_Tumor_Dashboard.png
│   │   └── Predicted_No_Tumor_Dashboard.png
│   └── GradCAM_Result.png
│
└── Documentation/
    └── Brain_Tumor_Project_Report.pdf
```

---

## Dataset

**Dataset:** Brain MRI Images for Brain Tumor Detection

* Total Images: **522**
* Tumor Images: **311**
* No Tumor Images: **211**
* Binary Classification Dataset
* Image Formats: JPEG, PNG

**Source**

https://www.kaggle.com/datasets/navoneel/brain-mri-images-for-brain-tumor-detection

> **Note:** The complete dataset is not included in this repository because of GitHub file size limitations.

---

## Installation

Clone the repository

```bash
git clone https://github.com/Hemanthhl/Explainable-AI-for-Brain-Tumor-Diagnosis-Using-EfficientNetB0-and-GradCAM.git
```

Install dependencies

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook

```bash
jupyter notebook
```

---

## Performance

| Metric    | Value      |
| --------- | ---------- |
| Accuracy  | **97.47%** |
| Precision | **97.62%** |
| Recall    | **97.47%** |
| F1-Score  | **97.48%** |

---

## Results

The proposed system successfully performs automated brain tumor detection using MRI images with EfficientNetB0.

Grad-CAM generates visual heatmaps highlighting tumor regions, improving transparency and interpretability.

The Gradio web application enables users to upload MRI images and receive real-time predictions along with tumor localization.

---

## Future Enhancements

* Multi-class brain tumor classification
* Brain tumor segmentation using U-Net
* Support for 3D MRI images
* Cloud deployment
* Mobile application for healthcare professionals
* Integration with hospital information systems

---

## Author

**Hemanth Gowda H L**

M.Sc. Data Science
REVA University, Bengaluru

**GitHub:** https://github.com/Hemanthhl

**LinkedIn:** https://www.linkedin.com/in/hemanth-gowdahl

---

## Acknowledgements

* Kaggle Brain MRI Images for Brain Tumor Detection Dataset
* TensorFlow
* Keras
* EfficientNetB0
* Gradio

---

## License

This project is licensed under the **MIT License**. See the **LICENSE** file for more details.
