# Pneumonia Detection with CNN (LeNet-5)

[![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)](https://www.python.org/)  
[![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange?logo=tensorflow)](https://www.tensorflow.org/)  
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)  

This project implements a **Convolutional Neural Network (CNN)** inspired by the **LeNet-5** architecture to classify chest X-ray images from the **PneumoniaMNIST** dataset (part of [MedMNIST](https://medmnist.com)).  
The goal is to distinguish between *Normal* and *Pneumonia* cases.

Training was carried out efficiently using TensorFlow and Keras, leveraging tf.data pipelines for optimized batching and prefetching. The model was evaluated with standard metrics such as accuracy, precision, recall, and F1-score, while results were further analyzed through visualizations including training curves, confusion matrices, and sample predictions.

## Technologies Used
- [Python 3.x](https://www.python.org/)  
- [TensorFlow / Keras](https://www.tensorflow.org/)  
- [NumPy](https://numpy.org/)  
- [Matplotlib](https://matplotlib.org/)  
- [Seaborn](https://seaborn.pydata.org/)  
- [Scikit-learn](https://scikit-learn.org/stable/)  
- [MedMNIST](https://medmnist.com)  
