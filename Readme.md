# ML-010: Handwritten Digit Recognition

A beginner-friendly Machine Learning and Computer Vision project that recognizes handwritten digits from 0 to 9 using Python and Scikit-learn.

## Project Overview

This project uses the built-in Digits dataset provided by Scikit-learn. Each image is an 8 × 8 grayscale image represented by 64 numerical pixel features.

A K-Nearest Neighbors (KNN) classifier is trained to predict handwritten digits and evaluated using accuracy, precision, recall, F1-score, and a confusion matrix.

## Features

- Uses a built-in dataset; no external image dataset required.
- Visualizes sample handwritten digits.
- Splits data into training and testing sets.
- Trains a KNN classifier.
- Evaluates model performance.
- Displays correct and incorrect predictions.
- Generates a confusion matrix.
- Saves and reloads the trained model.

## Tech Stack

- Python
- Jupyter Notebook
- NumPy
- Matplotlib
- Scikit-learn
- Joblib

## Dataset

- Source: `sklearn.datasets.load_digits()`
- Total images: 1,797
- Image dimensions: 8 × 8 pixels
- Features per image: 64
- Classes: 0–9

## Project Structure

```text
ML-010-Digit-Recognition/
├── ML_010_Handwritten_Digit_Recognition.ipynb
├── models/
│   └── knn_digits.joblib
├── requirements.txt
├── README.md
└── .gitignore
```

## Installation

Clone this repository and open the project folder:

```bash
git clone https://github.com/YOUR-USERNAME/ML-010-Digit-Recognition.git
cd ML-010-Digit-Recognition
```

Create a virtual environment and install dependencies:

```bash
python -m venv .venv
```

On Windows:

```bash
.venv\Scripts\activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Start Jupyter Notebook:

```bash
jupyter notebook
```

Open `ML_010_Handwritten_Digit_Recognition.ipynb` and run the cells.

## Model Evaluation

- Algorithm: K-Nearest Neighbors
- Number of neighbors: 3
- Training split: 80%
- Testing split: 20%
- Test accuracy: Add the actual measured accuracy here.

The confusion matrix and prediction galleries help identify classification errors.

## Limitations

The model is trained on small 8 × 8 images. It is not automatically designed to recognize arbitrary photographs or full-resolution handwritten digits without additional preprocessing and testing.

## Future Improvements

- Compare KNN with Logistic Regression.
- Test different values of K.
- Build an interactive digit-drawing interface.
- Experiment with image preprocessing and larger digit datasets.

## Learning Outcomes

This project demonstrates data loading, image representation, supervised classification, model evaluation, visualization, and model persistence.

## Author

Rajan Sharma

Machine Learning | Computer Vision | AI Engineering

---

Educational project for learning the fundamentals of machine learning.