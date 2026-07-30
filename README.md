#  Marine Debris Classifier

A computer vision project that leverages deep learning to detect and classify marine debris in underwater images. The project combines **image classification** and **real-time object detection** to distinguish **Marine Life** from **Plastic Debris**, demonstrating a complete machine learning workflow from data preparation to deployment.

The goal of this project is to explore how modern computer vision techniques can be applied to environmental monitoring and ocean conservation by automatically identifying plastic pollution in underwater imagery.

---

# Features

* Binary image classification (Marine Life vs. Plastic Debris)
* Real-time object detection using YOLO
* Image preprocessing and normalization
* Data balancing and augmentation
* Transfer learning with MobileNetV2
* Model evaluation and performance visualization
* Confidence score predictions
* Inference on unseen images
* Webcam and image-based detection using OpenCV
* Modular project structure for experimentation and future improvements

---

# Technologies Used

### Languages

* Python

### Machine Learning & Deep Learning

* TensorFlow
* Keras
* Ultralytics YOLO
* MobileNetV2 (Transfer Learning)

### Computer Vision

* OpenCV
* Pillow (PIL)

### Data Science

* NumPy
* Matplotlib

### Development Tools

* Jupyter Notebook
* UV
* Git
* GitHub

---

# Project Structure

```text
marine-debris-classifier/
│
├── data/
│
├── models/
│
├── notebooks/
│
├── src/
│
├── README.md
├── pyproject.toml
├── uv.lock
└── LICENSE
```

---

# Dataset

The dataset included in this repository was created by combining two publicly available Kaggle datasets.

* Marine Plastic Pollution Dataset
  https://www.kaggle.com/datasets/surajit651/souvikdataset

* Sea Animals Image Dataset
  https://www.kaggle.com/datasets/vencerlanz09/sea-animals-image-dataste

The images were cleaned, organized, balanced, and prepared for binary classification into two categories:

* Marine Life
* Plastic Debris

---

# Installation

Clone the repository:

```bash
git clone https://github.com/KinshukP/marine-debris-classifier.git
cd marine-debris-classifier
```

Install the project dependencies:

```bash
uv sync
```

Launch Jupyter:

```bash
uv run jupyter lab
```

---

# Machine Learning Pipeline

1. Data collection and exploration
2. Image preprocessing and normalization
3. Dataset balancing
4. Data augmentation
5. Transfer learning using MobileNetV2
6. Model training
7. Model evaluation
8. Object detection with YOLO
9. Live inference using OpenCV

---

# What I Learned

This project provided hands-on experience with the complete machine learning development lifecycle.

Throughout the project I learned how to:

* Build an end-to-end computer vision pipeline
* Prepare and balance image datasets
* Apply data augmentation techniques to improve generalization
* Use transfer learning to efficiently train image classification models
* Evaluate deep learning models using validation metrics
* Deploy trained models for inference on new images
* Integrate YOLO for real-time object detection
* Process webcam frames using OpenCV
* Organize a machine learning project using professional repository structure and version control with Git

---

# Future Improvements

* Expand to multiple marine debris categories
* Improve detection accuracy using larger and more diverse datasets
* Train a custom YOLO model specifically for underwater environments
* Deploy as a web application
* Optimize models for edge devices and mobile deployment

---

# License

Licensed under the MIT License.
