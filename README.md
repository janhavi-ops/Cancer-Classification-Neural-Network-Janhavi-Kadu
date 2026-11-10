# Cancer-Classification-Neural-Network-Janhavi-Kadu
# Cancer Classification Using Neural Networks

## 1. Project Overview

This project implements an Artificial Neural Network (ANN) to classify breast cancer tumours as **Benign** or **Malignant** using the Breast Cancer Wisconsin dataset.

The model learns patterns from numerical features extracted from cell nuclei and predicts the tumour category.

## 2. Project Objective

The main objectives are:
- To understand the application of neural networks in classification.
- To preprocess and analyze the breast cancer dataset.
- To build and train an Artificial Neural Network.
- To classify tumours into benign and malignant categories.
- To evaluate the model using different performance metrics.

## 3. Dataset Description

**Dataset:** Breast Cancer Wisconsin Dataset

The dataset is obtained using Scikit-learn's built-in dataset loader.

| Property | Description |
|---|---|
| Total samples | 569 |
| Total features | 30 |
| Classes | 2 |
| Class 1 | Malignant |
| Class 2 | Benign |
| Training data | 80% |
| Testing data | 20% |

The dataset contains numerical features such as radius, texture, perimeter, area, smoothness and other measurements of cell nuclei.

## 4. Technologies Used

- Python
- Google Colab
- TensorFlow
- Keras
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

## 5. Methodology

The project follows these steps:

1. Import the required Python libraries.
2. Load the Breast Cancer Wisconsin dataset.
3. Explore the dataset and its features.
4. Split the dataset into training and testing sets.
5. Apply feature scaling using StandardScaler.
6. Build an Artificial Neural Network.
7. Train the model using training data.
8. Evaluate the model using testing data.
9. Generate accuracy and loss graphs.
10. Calculate precision, recall and F1-score.
11. Generate a confusion matrix.
12. Test the model with a sample prediction.

## 6. Neural Network Architecture

The ANN consists of the following layers:

| Layer | Configuration |
|---|---|
| Input Layer | 30 input features |
| Hidden Layer 1 | 16 neurons, ReLU |
| Dropout Layer | 0.2 |
| Hidden Layer 2 | 8 neurons, ReLU |
| Output Layer | 1 neuron, Sigmoid |

### Model Configuration

- Optimizer: Adam
- Loss Function: Binary Crossentropy
- Epochs: 50
- Batch Size: 16
- Validation Split: 20%

## 7. Model Evaluation

The model is evaluated using the following metrics:

- **Accuracy:** Overall correctness of predictions.
- **Precision:** Correctness of positive predictions.
- **Recall:** Ability to identify actual positive cases.
- **F1-score:** Balance between precision and recall.
- **Confusion Matrix:** Displays correct and incorrect classifications.

The actual test accuracy and classification metrics are available in the notebook output.

## 8. Results and Visualization

The project generates:
- Training and validation accuracy graph.
- Training and validation loss graph.
- Classification report.
- Confusion matrix.
- Sample tumour prediction.

Refer to the `screenshots` folder for execution results and visual outputs.

## 9. Project Files

- `Cancer_Classification_Neural_Network.ipynb` – Complete source code and implementation.
- `cancer_classification_model.keras` – Saved trained neural network model.
- `screenshots/` – Project execution screenshots and results.
- `README.md` – Project documentation.

## 10. How to Run the Project

1. Open the Jupyter Notebook in Google Colab.
2. Run the cells sequentially.
3. Import the required libraries.
4. Load and preprocess the dataset.
5. Train the neural network.
6. Evaluate the model and view the results.

No external dataset download is required because the dataset is available directly through Scikit-learn.

## 11. Conclusion

The project demonstrates the use of Artificial Neural Networks for breast cancer classification. The model analyzes numerical features from the Breast Cancer Wisconsin dataset and classifies tumours into benign and malignant categories.

This project provides practical understanding of data preprocessing, neural network training, binary classification and model evaluation.

## 12. Disclaimer

This project is developed for educational purposes only. Its predictions are not intended for medical diagnosis or clinical decision-making.
