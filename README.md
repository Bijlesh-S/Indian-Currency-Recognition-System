# 💰 Indian Currency Recognition System

A deep learning–based system that automatically recognizes Indian currency denominations from images using **Convolutional Neural Networks (CNNs)**.  
This project was built to demonstrate how AI can bridge accessibility, automation, and accuracy in real-world financial scenarios.

---

## 🧠 Overview  
Handling currency recognition manually can be error-prone — especially for the visually impaired or in automated financial systems.  
This project leverages **computer vision** and **deep learning** to detect and classify Indian currency notes like ₹10, ₹20, ₹50, ₹100, ₹200, and ₹500.  

The model was trained on a dataset of labeled currency note images and achieves high accuracy in recognizing notes under various lighting and orientation conditions.  

---

## 🎯 Project Objective  
To develop a robust and efficient system that can:  
- Identify the denomination of Indian currency notes.  
- Handle real-world variations such as rotation, background noise, and light changes.  
- Serve as a foundation for accessibility or fintech applications.

---

## ⚙️ Tech Stack  
- **Language:** Python  
- **Libraries:** TensorFlow, Keras, OpenCV, NumPy, Pandas, Matplotlib  
- **Environment:** Jupyter Notebook  

---

## 🚀 How It Works  
1. **Data Preprocessing:** Images are resized, normalized, and augmented to improve model generalization.  
2. **Model Training:** A CNN model is trained on labeled note images to learn visual patterns unique to each denomination.  
3. **Prediction:** The trained model can classify any new currency image into its correct denomination.  
4. **Evaluation:** Model performance is measured using accuracy, loss curves, and confusion matrices.  

---

## 🧠 Deep Learning Model  
The system uses a **Convolutional Neural Network (CNN)** architecture that includes:  
- Convolutional layers for feature extraction  
- MaxPooling layers for dimensionality reduction  
- Dense layers for classification  
- Softmax activation for final output  

The model was trained with **Adam optimizer** and **categorical cross-entropy loss**, ensuring efficient convergence and strong accuracy.

---

## 📊 Results  
- The CNN achieved **high accuracy** in classifying most denominations.  
- The model performs consistently well even under moderate lighting or rotation variations.  
- Further improvements can be made by adding more image samples for future currencies.  

---

## 🌟 Future Scope  
This project has strong potential for **real-world expansion** beyond research use:  
- 📱 **Mobile App Integration:** Convert the model using TensorFlow Lite to enable on-device recognition.  
- 🌐 **Web Application:** Deploy the model with a Flask/Django backend for live currency detection.  
- 🗣️ **Voice Assistance:** Integrate a text-to-speech system to announce the recognized note value for visually impaired users.  
- 💼 **Banking & Fintech Use:** Implement in ATMs or cash-counting machines for real-time validation.  

---

## 🤝 Contributions  
If you’d like to improve accuracy, extend the dataset, or optimize model performance — contributions are welcome!  
Feel free to fork the repository, raise issues, or open pull requests.

---

## 📄 License  
This project is released under the **MIT License** — free to use, modify, and distribute with attribution.

---

## ✨ Author  
**Bijlesh S**  
📧 bijleshsathishkumar@gmail.com  
🌐 https://github.com/Bijlesh-S
