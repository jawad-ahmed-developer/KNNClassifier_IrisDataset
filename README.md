# Iris Flower Classification using K-Nearest Neighbors (KNN)

## Project Overview

This project implements a **K-Nearest Neighbors (KNN)** classification model on the Iris dataset using Python and Scikit-learn. The goal is to classify iris flowers into their respective species based on sepal and petal measurements.

The project covers the complete machine learning workflow, including data exploration, visualization, preprocessing, model training, evaluation, and prediction on unseen samples.

---

## Dataset

The Iris dataset contains **150 samples** belonging to three flower species:

* Setosa
* Versicolor
* Virginica

Each sample includes the following features:

| Feature      | Description              |
| ------------ | ------------------------ |
| Sepal Length | Length of the sepal (cm) |
| Sepal Width  | Width of the sepal (cm)  |
| Petal Length | Length of the petal (cm) |
| Petal Width  | Width of the petal (cm)  |

---

## Features Implemented

### Data Exploration

* Loaded the Iris dataset using Scikit-learn.
* Converted the dataset into a Pandas DataFrame.
* Examined dataset structure and summary statistics.

### Data Visualization

* Generated pair plots using Seaborn.
* Visualized feature distributions and class separability.

### Data Preprocessing

* Applied feature scaling using `StandardScaler`.
* Created normalized datasets for improved model performance.

### Model Training

* Split data into training and testing sets.
* Trained a K-Nearest Neighbors classifier with `k = 5`.

### Model Evaluation

The model was evaluated using:

* Accuracy Score
* Precision Score
* Recall Score
* F1 Score
* Confusion Matrix

### Custom Sample Testing

* Created additional test samples with similar feature patterns.
* Evaluated model behavior on challenging classification cases.
* Visualized prediction performance using a confusion matrix.

---

## Technologies Used

* Python
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn

---


## Running the Project

Either run .py file on any python IDE or editor or run .ipynb file on google colab

## Results

The KNN model successfully classifies Iris flower species with high accuracy after feature normalization. Performance metrics and confusion matrices provide insight into the model's effectiveness and its behavior on more challenging samples.

---

## Key Learning Outcomes

* Exploratory Data Analysis (EDA)
* Data Visualization
* Feature Scaling and Normalization
* K-Nearest Neighbors Classification
* Model Evaluation Techniques
* Confusion Matrix Interpretation
* Working with Real-World Machine Learning Workflows


## License

This project is available for educational and learning purposes.
