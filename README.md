# Cat and Dog Image Classification using HOG and SVM

This project aims to classify images of cats and dogs using the Histogram of Oriented Gradients (HOG) feature extraction technique combined with a Support Vector Machine (SVM) classifier. The method extracts features from images and uses SVM to classify them into two categories: cats and dogs.

## Table of Contents

- [Introduction](#introduction)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)


## Introduction

Image classification is a crucial task in computer vision, where the goal is to assign labels to images based on their content. In this project, we focus on classifying images of cats and dogs. By using HOG for feature extraction and SVM for classification, we build a model capable of distinguishing between these two animals.

## Requirements

To run this project, you need to install the following libraries and tools:

- Python 3.7 or higher
- Jupyter Notebook
- OpenCV
- scikit-learn
- NumPy
- Matplotlib

## Installation

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/quangkmhd/SVM_Cats_Dog.git
   cd SVM_Cats_Dog
   ```

2. **Create a Virtual Environment**:

   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows, use 'venv\Scripts\activate'
   ```

3. **Install Dependencies**:

   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. **Prepare the Dataset**:
   - Place cat images in `data/cats/`
   - Place dog images in `data/dogs/`

2. **Extract HOG Features and Train the SVM Model**:
   - Open the Jupyter Notebook `train-classification-svm-hog.ipynb`
   - Run each cell to extract features and train the model

3. **Evaluate the Model**:
   - Use the test set to assess model performance using accuracy, precision, recall, and confusion matrix.

4. **Make Predictions on New Images**:
   - Use the trained model to classify new images by running the appropriate notebook cells.




