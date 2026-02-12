# Customer Churn Prediction using Artificial Neural Networks (ANN)

## 📌 Project Overview
This project focuses on building an Artificial Neural Network (ANN) to predict whether a bank customer is likely to leave (churn) based on various factors like credit score, geography, gender, age, and balance.

I built this model using **Python** and **TensorFlow/Keras** as part of my deep learning journey.

## 📊 Dataset
The project uses the **Churn Modelling Dataset** from Kaggle.
- **Features:** Credit Score, Geography, Gender, Age, Tenure, Balance, Number of Products, Has Credit Card, Is Active Member, and Estimated Salary.
- **Target Variable:** `Exited` (1 if the customer left, 0 if they stayed).

## 🛠️ Tech Stack
- **Language:** Python
- **Environment:** Google Colab
- **Libraries:**
  - `Pandas` & `NumPy`: For data manipulation.
  - `Scikit-learn`: For data scaling and splitting.
  - `TensorFlow / Keras`: To build and train the neural network.
  - `Matplotlib`: For visualizing training accuracy.

## 🧠 Model Architecture
The ANN is constructed with the following layers:
1. **Input Layer**: Takes in the preprocessed customer data.
2. **Hidden Layers**: Five dense layers with `ReLU` activation functions (ranging from 10 to 28 neurons).
3. **Output Layer**: One neuron with a `Sigmoid` activation function to predict probability.

## 📈 Visualizations
Inside the `Pictorial Representation of ANN` folder, you will find:
- **Architecture Diagrams**: Visual flow of how neurons are connected.
- **Training Plots**: Graphs showing how the model's accuracy improved over 100 epochs.

## 🚀 How to Run
1. Open the `.ipynb` file in Google Colab.
2. Ensure you have `kagglehub` installed to fetch the dataset.
3. Run all cells to see the training process and the final accuracy graph.

---
**Author:** Sana Khan
