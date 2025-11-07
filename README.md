💵 Indian Currency Recognition System
📘 Project Overview

The Indian Currency Recognition System is a Deep Learning project that automatically identifies the denomination of Indian currency notes from images. The model leverages Convolutional Neural Networks (CNNs) to classify various denominations with high accuracy.

⚠️ Note: The model currently supports denominations except the ₹2000 note.

🎯 Objective

To develop a deep learning model capable of recognizing Indian currency denominations from digital images using CNN-based image classification.

🧠 Features

Image preprocessing and normalization for better model performance

Training a CNN model for multi-class currency classification

Visualizing accuracy and loss using plots

Testing model predictions on new currency note images

Scalable architecture for future extension to mobile and web applications

🧰 Tech Stack

Programming Language: Python

Framework: TensorFlow / Keras

Environment: Jupyter Notebook

Libraries Used:

NumPy

Pandas

Matplotlib

TensorFlow

Keras

🧩 Dataset

Dataset Name: Indian Currency Dataset
Source: Manually collected or publicly available Indian currency images
Description: Contains labeled images of different denominations (₹10, ₹20, ₹50, ₹100, ₹200, ₹500).

🧠 Model Overview

Model Type: Convolutional Neural Network (CNN)

Input: Preprocessed images of currency notes

Output: Predicted denomination class

Optimizer: Adam

Loss Function: Categorical Crossentropy

Evaluation Metric: Accuracy

📊 Results

The trained CNN achieved high accuracy on validation data.

Successfully recognized most denominations except ₹2000 notes.

Visualization plots clearly depict training and validation trends.

🚀 Future Scope

📱 Mobile Application:
Develop an Android/iOS app that uses the trained deep learning model to recognize currency in real-time using a smartphone camera.

🌐 Web-Based Interface:
Create a web application where users can upload images of currency notes for instant denomination prediction.

🔍 Fake Currency Detection:
Extend the system to detect counterfeit notes using watermark and texture analysis.

🧠 Model Optimization:
Convert the CNN model to TensorFlow Lite for lightweight deployment on mobile devices.

♿ Accessibility Features:
Add voice feedback for visually impaired users to help them identify denominations easily.

⚙️ How to Run the Project

Clone this repository:

git clone https://github.com/Bijlesh-S/Indian-Currency-Recognition-System.git


Navigate to the project directory:

cd Indian-Currency-Recognition-System


Open the Jupyter Notebook:

jupyter notebook Indian_Currency_Recognition_System_DL_mini_project.ipynb


Run all cells sequentially to train and test the model.

🧾 License

This project is open-source and available under the MIT License.

👨‍💻 Author

Bijlesh S
Deep Learning Mini Project — Indian Currency Recognition System
