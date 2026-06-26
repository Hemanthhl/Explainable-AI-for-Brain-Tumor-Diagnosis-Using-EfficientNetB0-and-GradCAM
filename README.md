# 🧠 Explainable AI for Brain Tumour Diagnosis Using EfficientNetB0 and Grad-CAM

## Overview

The **Explainable AI for Brain Tumour Diagnosis Using EfficientNetB0 and Grad-CAM** is a Deep Learning and Explainable Artificial Intelligence (XAI) project designed to automatically detect brain tumours from MRI images. The system uses **EfficientNetB0** for accurate tumour classification and **Grad-CAM** to generate visual heatmaps that highlight tumour regions, making the model's predictions transparent and interpretable.

The project aims to assist healthcare professionals by providing fast, accurate, and explainable brain tumour diagnosis. An interactive **Gradio-based web application** allows users to upload MRI images and receive real-time predictions along with tumour localization.

---

## Objectives

* Detect brain tumours automatically from MRI images.
* Classify MRI scans into **Tumour** and **No Tumour** categories.
* Improve classification accuracy using EfficientNetB0 transfer learning.
* Generate Grad-CAM heatmaps for explainable AI.
* Visualize tumour regions for better model interpretability.
* Evaluate model performance using standard classification metrics.
* Provide a user-friendly Gradio interface for prediction.

---

## Features

* Brain MRI Image Classification
* EfficientNetB0 Transfer Learning
* Explainable AI using Grad-CAM
* Tumour Localization with Heatmaps
* Image Preprocessing and Data Augmentation
* Binary Classification (Tumour / No Tumour)
* Performance Evaluation using Accuracy, Precision, Recall and F1-Score
* Gradio-based Web Interface

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
Explainable-AI-for-Brain-Tumour-Diagnosis-Using-EfficientNetB0-and-GradCAM
│
├── README.md
├── requirements.txt
├── disease_prediction.ipynb
├── brain_tumor_classifier.keras
├── LICENSE
│
├── Dataset/
│   ├── README.md
│   └── Dataset_Link.txt
│
├── Images/
│   ├── Architecture.png
│   ├── Dataset.png
│   ├── GradCAM_Output.png
│   ├── Confusion_Matrix.png
│   ├── Accuracy_Graph.png
│   ├── Loss_Graph.png
│   ├── ROC_Curve.png
│   └── Gradio_Interface.png
│
├── Output/
│   ├── Prediction1.png
│   ├── Prediction2.png
│   └── Heatmap1.png
│
└── Research_Paper/
    └── Conference_Paper.pdf
```

---

## Dataset

**Dataset:** Brain MRI Images for Brain Tumor Detection

* Total Images: **522**
* Tumour Images: **311**
* No Tumour Images: **211**
* Binary Classification Dataset
* Image Formats: JPEG, PNG

**Source:** Kaggle

https://www.kaggle.com/datasets/navoneel/brain-mri-images-for-brain-tumor-detection

**Note:** The complete dataset is not included in this repository because of GitHub file size limitations. Please download it separately from the original source.

---

## Installation

Clone the repository.

```bash
git clone https://github.com/Hemanthhl/Explainable-AI-for-Brain-Tumour-Diagnosis-Using-EfficientNetB0-and-GradCAM.git
```

Install the required libraries.

```bash
pip install -r requirements.txt
```

Run the Gradio application.

```bash
python app.py
```

---

## Results

The proposed system successfully performs automated brain tumour detection using MRI images and EfficientNetB0. Grad-CAM generates heatmaps to highlight tumour regions, improving the transparency and interpretability of the model. The system achieved approximately **97.47% classification accuracy** and provides a user-friendly Gradio interface for real-time prediction and visualization.

---

## Future Enhancements

* Multi-class brain tumour classification
* Brain tumour segmentation using U-Net
* Support for 3D MRI images
* Cloud deployment for remote diagnosis
* Mobile application for healthcare professionals
* Integration with hospital information systems

---

## Author

**Hemanth Gowda H L**

M.Sc. Data Science
REVA University, Bengaluru

**LinkedIn:** https://www.linkedin.com/in/hemanth-gowdahl

**GitHub:** https://github.com/Hemanthhl

---

## License

This project is developed for educational and research purposes.
