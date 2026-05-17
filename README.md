1-📌 Problem Description
  This project uses a Multilayer Perceptron (MLP) built with PyTorch to predict house prices 
  based on features like income, house age, number of rooms, population, and location.
  This project aims to compare the performance of different activation functions 
  and optimizers in a neural network regression task.

Two experiments were conducted:
    Experiment 1: Using ReLU activation
    Experiment 2: Using Tanh activation

The goal is to evaluate each model using MSE and RMSE to determine which configuration provides better predictive accuracy.

2-📂 Dataset Link:

You can download the dataset used in this project from the following link:
(https://scikit-learn.org/stable/datasets/real_world.html#california-housing-dataset)

3-📊 Results (Comparison Table):

| Experiment   | Activation Function | MSE    | RMSE   |
| ------------ | ------------------- | ------ | ------ |
| Experiment 1 | ReLU                | 0.4842 | 0.6959 |
| Experiment 2 | Tanh                | 0.5004 | 0.7074 |


4-▶️ Instructions for Running the Project:
    Option 1 – Google Colab (Recommended)
       1- Open Google Colab
       2- Upload house_price_ann.py or paste the code into a new notebook
       3- Run all cells — dataset downloads automatically via sklearn
    Option 2 – Local Machine
    1️⃣ Requirements:
         python >= 3.8
         torch
         scikit-learn
         numpy
         matplotlib
    2️⃣Install dependencies:
          pip install torch scikit-learn numpy matplotlib
    3️⃣ Run Training
          python house_price_ann.py

👤 Author
    John Ayman makram
    Faculty of Artificial Intelligence – Badr Assiut University
    Department of Information Technology – Year 3







    
