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

 House Price Prediction using ANN (MLP)

Neural Networks Course – ANN Project
Faculty of Artificial Intelligence – Badr Assiut University
Department of Information Technology – Year 3


📌 Problem Description
This project uses a Multilayer Perceptron (MLP) built with PyTorch to predict house prices based on features like income, house age, number of rooms, population, and location.
This is a regression task — the model outputs a continuous value (median house price in $100,000s).
Two experiments are compared using different activation functions, learning rates, and network sizes to analyze their effect on performance.

📦 Dataset
California Housing Dataset
PropertyValueSourcesklearn.datasets.fetch_california_housingSamples20,640Features8TargetMedian house value (×$100,000)Missing valuesNone
Features used:
FeatureDescriptionMedIncMedian income in block groupHouseAgeMedian house ageAveRoomsAverage number of roomsAveBedrmsAverage number of bedroomsPopulationBlock group populationAveOccupAverage house occupancyLatitudeBlock group latitudeLongitudeBlock group longitude
🔗 Dataset Documentation

🧠 Model Architecture
Input Layer   →  8 features
Hidden Layer 1 →  Dense(N)   + Activation (ReLU / Tanh)
Hidden Layer 2 →  Dense(N)   + Activation (ReLU / Tanh)
Output Layer  →  Dense(1)   — linear (no activation)
Built with PyTorch (nn.Module).

⚙️ Experiments
Experiment 1Experiment 2ActivationReLUTanhLearning Rate0.0010.0005Hidden Neurons64128OptimizerAdamAdamLoss FunctionMSEMSEEpochs200200

📊 Results
ExperimentActivationLRNeuronsMSERMSEExp 1ReLU0.001640.45800.6768Exp 2Tanh0.00051280.50710.7121

RMSE is in the same unit as the target (×$100k).
Lower MSE = better model.
🏆 Experiment 1 (ReLU) achieved better performance.


🚀 How to Run
Option 1 – Google Colab (Recommended)

Open Google Colab
Upload house_price_ann.py or paste the code into a new notebook
Run all cells — dataset downloads automatically via sklearn

Option 2 – Local Machine
Requirements:
python >= 3.8
torch
scikit-learn
numpy
matplotlib
Install dependencies:
bashpip install torch scikit-learn numpy matplotlib
Run:
bashpython house_price_ann.py

📁 Repository Structure
📦 house-price-ann/
 ┣ 📄 house_price_ann.py     ← Main source code
 ┣ 📄 README.md              ← This file

👤 Author
John Ayman
Faculty of Artificial Intelligence – Badr Assiut University
Department of Information Technology – Year 3





    
