# Brain MRI Images for Brain Tumor Detection

## Dataset Description

This project uses the **Brain MRI Images for Brain Tumor Detection** dataset, which is publicly available on **Kaggle**. The dataset contains brain Magnetic Resonance Imaging (MRI) scans collected from multiple subjects under different imaging conditions. It is widely used for research and educational purposes in deep learning-based brain tumour classification.

## Dataset Information

* **Dataset Name:** Brain MRI Images for Brain Tumor Detection
* **Source:** Kaggle
* **Image Type:** Brain MRI Images
* **Classification Type:** Binary Classification
* **Classes:**

  * Tumour
  * No Tumour
* **Total Images:** 522
* **Tumour Images:** 311
* **No Tumour Images:** 211
* **Image Formats:** JPEG (.jpg), PNG (.png)
* **Input Size:** 224 × 224 pixels
* **Color Mode:** RGB (after preprocessing)

## Preprocessing

Before training the model, all MRI images undergo several preprocessing steps:

* Image resizing to **224 × 224** pixels
* RGB color conversion
* Pixel value normalization
* Data augmentation including:

  * Rotation
  * Horizontal Flip
  * Zoom

These preprocessing techniques improve model generalization and reduce overfitting.

## Dataset Source

Kaggle Dataset:

https://www.kaggle.com/datasets/navoneel/brain-mri-images-for-brain-tumor-detection

## Note

The complete dataset is **not included** in this repository due to GitHub file size limitations. Please download the dataset from the official Kaggle source before running the project.
