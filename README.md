#  Breast Cancer Classification Using Neural Network

## **Project Overview** 

This project focuses on classifying breast cancer as either malignant or benign using a neural network. The classification is based on various features derived from breast cancer cell images. The project utilizes a dataset, processes the data, builds a neural network model, and evaluates its performance.

__Dataset__

The dataset used for this project is the Breast Cancer Wisconsin (Diagnostic) Data Set. It includes 569 instances of different breast cancer cell images, each described by 30 features. The target variable indicates whether the cancer is malignant or benign.

## **Features**

The dataset consists of the following features:

+ Radius
+ Texture
+ Perimeter
+ Area
+ Smoothness
+ Compactness
+ Concavity
+ Concave points
+ Symmetry
+ Fractal dimension
+ And more...

## **Project Structure**

- **Breast Cancer Classification.ipynb**: The main Jupyter Notebook containing all the code for data preprocessing, model building, training, and evaluation.

## **Neural Network Model**

The neural network model is built using Keras and TensorFlow. It consists of the following layers:
- **Input layer**
- **Hidden layers**
- **Output layer**

The model is trained using the dataset, and various metrics are used to evaluate its performance, including accuracy.

## **Installation**

To run this project, you need to have Python installed along with the following libraries:
- **numpy**
- **pandas**
- **matplotlib**
- **seaborn**
- **scikit-learn**
- **tensorflow**
- **keras**

You can install the required libraries using the following command:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn tensorflow keras
```
## **Results**

The model achieves an accuracy of 96.49%



