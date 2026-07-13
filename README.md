# Bird & Cat Image Classification with Google Teachable Machine

## Project Overview

This project demonstrates an image classification model built using Google Teachable Machine. The model was trained to classify images into two categories: Bird and Cat. After training, the model was exported in TensorFlow/Keras format and tested using Google Colab with Python.

---

## Image Classes

- Class 1: Bird thatt was tested
- Class 2: Cat

---

## Tools & Technologies

- Google Teachable Machine
- TensorFlow / Keras
- Python
- Google Colab
- NumPy
- Pillow (PIL)

---

## Teachable Machine

The model was trained using Google Teachable Machine with two classes: Bird and Cat. After training, the preview feature was used to test a bird image, and the model correctly predicted it as Bird with 100% confidence.

| Training Model | Test Image | Prediction |
|:--------------:|:----------:|:----------:|
| ![](screenshots/photo_2026-07-13_03-36-30.jpg) | ![](screenshots/photo_2026-07-13_03-37-13.jpg) | ![](screenshots/photo_2026-07-13_03-37-41.jpg) |

---

## Google Colab

The exported TensorFlow/Keras model was loaded into Google Colab using Python. The notebook loads the trained model, processes the input image, and predicts its corresponding class.

| Google Colab Notebook | Prediction Result |
|:----------------------:|:-----------------:|
| ![](screenshots/photo_2026-07-13_03-38-43.jpg) | ![](screenshots/photo_2026-07-13_03-39-00.jpg) |

---

## Repository Contents

- keras_model.h5 – Trained TensorFlow/Keras model.
- labels.txt – Class labels.
- Untitled0.ipynb – Google Colab notebook.
- download (5).jpeg – Test image.
- screenshots
- README.md 

---

## Conclusion

The model was trained to recognize birds and cats. It was tested in Google Colab and successfully predicted the bird image correctly.

Turki Alkhelaiwi for Smart Methods Summer Training
