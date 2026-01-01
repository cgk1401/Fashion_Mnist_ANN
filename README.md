# Fashion Image Classification with Fashion-MNIST

This project uses **Deep Learning** (with **TensorFlow** and **Keras**) to build a model that classifies fashion items from the **Fashion-MNIST** dataset.

---

## 📌 Project Overview

The objective of this project is to train an **Artificial Neural Network (ANN)** capable of recognizing **10 different fashion categories** from grayscale images of size **28×28 pixels**.

### Class Labels

The model is trained to classify the following categories:

- 0: T-shirt/top  
- 1: Trouser  
- 2: Pullover  
- 3: Dress  
- 4: Coat  
- 5: Sandal  
- 6: Shirt  
- 7: Sneaker  
- 8: Bag  
- 9: Ankle boot  

---

## 📊 Dataset

- **Source:** `keras.datasets.fashion_mnist`
- **Size:**  
  - 60,000 images for training  
  - 10,000 images for testing
- **Image format:**  
  - Grayscale images  
  - Each image is represented as a **28×28 NumPy array**

---

## 🛠 Tools and Libraries

The project is implemented using the following Python libraries:

- **TensorFlow & Keras** – model building and training  
- **NumPy** – numerical and array operations  
- **Matplotlib** – image and result visualization  
- **Random** – random data sampling  

---

## 🚀 Workflow

The project follows these main steps:

1. **Data Loading**  
   The dataset is loaded directly from Keras.

2. **Data Exploration**  
   Random samples are visualized along with their corresponding labels to better understand the dataset.

3. **Preprocessing**  
   Data is prepared and reshaped appropriately before being fed into the neural network.

4. **Model Construction**  
   A deep learning model is defined using fully connected (Dense) layers.

5. **Training**  
   The model is trained on the training dataset.

6. **Evaluation**  
   The trained model is evaluated on the test dataset to measure its performance.

---

## 📈 Results

After training, the model is able to predict different fashion categories with relatively good accuracy based on input images.

---

