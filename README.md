#  Marine Debris Classifier

A computer vision project that classifies underwater images as either **Marine Life** or **Plastic Debris** using deep learning.

The project demonstrates a complete machine learning workflow, including dataset preparation, image preprocessing, data augmentation, transfer learning, model training, and prediction on unseen images.

---

## Features

- Binary image classification
- Image preprocessing pipeline
- Data augmentation
- Transfer learning with Convolutional Neural Networks (CNNs)
- Model evaluation and visualization
- Prediction on unseen images

---

## Technologies Used

- Python
- Jupyter Notebook
- NumPy
- Pillow (PIL)
- Matplotlib
- TensorFlow / Keras *(coming soon)*

---

## Project Structure

```text
marine-debris-classifier/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
├── src/
│
├── README.md
├── pyproject.toml
├── uv.lock
└── LICENSE
```

---

## Dataset

This project uses two publicly available Kaggle datasets.

### Marine Plastic Pollution
https://www.kaggle.com/datasets/surajit651/souvikdataset

### Sea Animals Image Dataset
https://www.kaggle.com/datasets/vencerlanz09/sea-animals-image-dataste

The datasets are **not included** in this repository due to GitHub storage limitations.

Place the extracted datasets inside:

```text
data/
└── raw/
    ├── marine-plastic/
    └── sea-animals/
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/<your-username>/marine-debris-classifier.git
cd marine-debris-classifier
```

Create the environment and install dependencies:

```bash
uv sync
```

Launch Jupyter Lab:

```bash
uv run jupyter lab
```

Open:

```text
notebooks/week1_data_preprocessing.ipynb
```

---

## License

This project is licensed under the MIT License.
