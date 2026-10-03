# Cats vs Dogs CNN

## 📌 Project Overview

This project focuses on **image classification** using a Convolutional Neural Network (CNN).

The goal is to classify images into two classes:

* 🐱 Cats
* 🐶 Dogs

The project was implemented and trained using **Kaggle** with **TensorFlow/Keras**.

## 🖼️ Dataset

The project uses an image dataset containing two classes:

* Cats
* Dogs

The images are prepared and loaded using TensorFlow/Keras image processing tools.

## 🛠️ Technologies & Libraries

* Python
* TensorFlow
* Keras
* NumPy
* Matplotlib
* Convolutional Neural Networks (CNN)
* Kaggle

## 🔄 Project Workflow

The project follows these main steps:

1. Load the image dataset
2. Prepare the image data
3. Resize the images
4. Normalize pixel values
5. Apply data augmentation
6. Create training and validation data generators
7. Build a CNN model
8. Compile the model
9. Train the model
10. Use Early Stopping
11. Evaluate the model
12. Visualize training and validation performance
13. Test the model on an individual image

## 🧠 CNN Model

The project uses a **Convolutional Neural Network** for image classification.

The CNN learns visual features from the images and uses these features to classify an image as either a cat or a dog.

## 🔧 Image Preprocessing

The project includes several preprocessing steps:

* Image resizing
* Pixel normalization
* Data augmentation
* Training/validation data generation

Data augmentation helps provide variation in the training images and can help the model learn more robust visual patterns.

## 📈 Model Training & Evaluation

The model training process includes:

* Training and validation datasets
* Multiple training epochs
* Early Stopping
* Accuracy monitoring
* Loss monitoring

The notebook also includes graphs for:

* Training vs. validation accuracy
* Training vs. validation loss

## 🔍 Prediction

After training, the model can be used to classify an individual image as:

```text
Cat
```

or

```text
Dog
```

## ☁️ Environment

This project was developed and executed using **Kaggle**.

The notebook can be opened and run in a Kaggle Notebook environment with the required dataset and dependencies.

## 📁 Project Structure

```text
Cats-vs-Dogs-CNN/
│
├── CatsVsDogs_CNN_Assignment.ipynb
└── README.md
```

The complete image dataset is not included in this repository.

## ▶️ How to Run

### Option 1 — Kaggle

Open the notebook in Kaggle and make sure the required dataset is attached to the notebook.

Then run the notebook cells from top to bottom.

### Option 2 — Local Environment

Install TensorFlow and the other required libraries:

```bash
pip install tensorflow numpy matplotlib
```

Then open:

```text
CatsVsDogs_CNN_Assignment.ipynb
```

using Jupyter Notebook, JupyterLab, or Visual Studio Code.

The dataset paths may need to be adjusted when running outside Kaggle.

## 🎯 Project Goal

The main goal of this project was to gain practical experience with:

* Deep Learning
* Computer Vision
* CNN architectures
* Image preprocessing
* Data augmentation
* Model training
* Model evaluation
* Image classification
* TensorFlow/Keras

## 👨‍💻 Author

**Mazen Mohamed El Sayed**

Computer Science Student | Data Science & Machine Learning
