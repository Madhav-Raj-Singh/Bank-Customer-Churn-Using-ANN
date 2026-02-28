Bank Customer Churn Prediction using ANN
This project implements a Deep Learning model to predict whether a customer will leave a bank (churn) based on various demographic and financial factors. It uses an Artificial Neural Network (ANN) built with TensorFlow and Keras to perform binary classification.
📊 Dataset Overview
The model is trained on a dataset containing 10,000 customer records. Key features used for prediction include:
• Credit Score, Geography, and Gender
• Age and Tenure
• Balance and Number of Products
• Credit Card Status, Active Membership, and Estimated Salary
🛠️ Technical Stack
• Language: Python
• Libraries: Pandas, NumPy, Scikit-learn (for preprocessing)
• Deep Learning: TensorFlow/Keras
• Environment: Google Colab
🧠 Model Architecture
The ANN consists of a sequential input-to-output structure:
1. Input Layer: 11 features.
2. Hidden Layers: * Dense layer (11 neurons, ReLU activation) with 30% Dropout.
• Dense layer (7 neurons, ReLU activation) with 30% Dropout.
• Dense layer (6 neurons, ReLU activation).
3. Output Layer: 1 neuron with Sigmoid activation for binary classification.
4. Optimization: Adam optimizer and Binary Cross-Entropy loss.
5. Training: Utilized Early Stopping to prevent overfitting, monitoring validation loss with a patience of 20 epochs.
📈 Performance Results
The model was evaluated using a test split of 33%.
Accuracy=85%

🚀 How to Run
1. Ensure you have the Churn_Modelling.csv file.
2. Run the provided Jupyter Notebook (.ipynb) in a Google Colab or local Jupyter environment.
3. Install dependencies: pip install tensorflow pandas numpy scikit-learn.
