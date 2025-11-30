📘 CNN & RNN Deep Learning Project

A comprehensive Google Colab project demonstrating CNNs, LSTMs, Bidirectional LSTMs, CNN–LSTM hybrids & Hyperparameter Tuning

🔍 Overview

This project showcases multiple deep learning architectures implemented using TensorFlow/Keras.
It includes both image classification (CNN) and text sentiment analysis (RNN) to demonstrate how deep learning models behave on different data types.

The notebook is built and executed on Google Colab, making it accessible and easy to run.

📁 Project Structure
├── CNN (MNIST)
│   ├── Data Loading
│   ├── CNN Architecture
│   ├── Training & Plots
│   └── Evaluation
│
├── RNN Models (IMDB)
│   ├── Simple LSTM
│   ├── Bidirectional LSTM
│   ├── CNN–LSTM Hybrid
│   ├── Hyperparameter Tuning (Keras Tuner)
│   └── Model Comparison
│
└── README.md

🎯 Objectives

This project demonstrates:

🔹 Convolutional Neural Networks (CNN)

Image classification on MNIST

Convolution + Pooling

Dense and Softmax layers

🔹 Recurrent Neural Networks (RNN)

Sentiment analysis using IMDB dataset

Sequence modeling with embeddings

🔹 Advanced Architectures

Bidirectional LSTM

CNN–LSTM Hybrid

Hyperparameter Tuning using Keras Tuner

🔹 Evaluation Tools

Accuracy curves

Validation metrics

Model comparison table (accuracy, parameters)

🧠 Models Implemented
1️⃣ CNN (MNIST)

Conv2D → MaxPooling → Conv2D → MaxPooling → Dense

Trains fast and achieves high accuracy on image data

2️⃣ Simple LSTM (IMDB)

Embedding → LSTM → Dense

Learns sequential dependencies from text

3️⃣ Bidirectional LSTM

Reads text in forward + backward direction

Improved context understanding

4️⃣ CNN–LSTM Hybrid

CNN extracts local n-gram features

LSTM reads temporal sequence

Often performs better on longer text

5️⃣ Tuned LSTM Model

Hyperparameters tuned:

LSTM units

Dropout rate

Learning rate

📊 Model Comparison
Model	Test Accuracy	Trainable Params
Simple LSTM	~X%	~Y
Bidirectional LSTM	~X%	~Y
CNN–LSTM Hybrid	~X%	~Y
Best Tuned Model	~X%	~Y

(Values update automatically inside the notebook.)

🚀 Technologies Used

Python

TensorFlow / Keras

Keras Tuner

Matplotlib

Pandas

Google Colab

▶️ How to Run

Open the .ipynb file in Google Colab

Install required dependencies:

!pip install tensorflow keras-tuner matplotlib


Run all the cells sequentially

View results, plots, and comparison tables

📈 Results Summary

CNN achieves strong accuracy on MNIST

Bidirectional LSTM shows improved performance over standard LSTM

CNN–LSTM gives balanced pattern extraction + sequence modeling

Hyperparameter tuning significantly boosts performance

📌 Future Enhancements

Transformer-based models (BERT, GPT-style)

Data augmentation for MNIST

Attention mechanism for IMDB

Deployment via Flask or FastAPI

🏷️ Author
Jyothi Sasidharan
Machine Learning & AI Enthusiast
(With background in ECE, MBA HR & Marketing)
Jyothi S
Machine Learning & AI Enthusiast
(With background in ECE, MBA HR & Marketing)
