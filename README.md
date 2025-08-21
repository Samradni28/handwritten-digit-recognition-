# 🧠 Handwritten Digit Recognition using Neural Networks  

This project demonstrates a **beginner-friendly deep learning model** for classifying handwritten digits (0–9) from the **MNIST dataset**. It introduces the fundamental workflow of building, training, and evaluating a neural network using **Keras (TensorFlow backend)**.  

---

## 📂 Project Workflow  
1. **Dataset Import** – Loaded MNIST dataset directly from Keras.  
2. **Preprocessing** – Flattened 28×28 grayscale images into vectors & normalized pixel values.  
3. **Train-Test Split** – 60,000 images for training, 10,000 for testing.  
4. **Model Architecture**  
   - `Flatten` layer → Dense hidden layers with **ReLU**  
   - Output layer with **Softmax** activation for 10-class classification  
5. **Training**  
   - **Optimizer:** Adam  
   - **Loss Function:** Categorical Crossentropy  
6. **Evaluation** – Achieved ~97–98% accuracy on test data.  

---

## ⚙️ Tech Stack  
- **Language:** Python  
- **Libraries:** TensorFlow / Keras, NumPy, Matplotlib  

---
