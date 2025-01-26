# MNIST Classification Improvement Project

This project focuses on improving the accuracy of a classification model trained on the MNIST dataset. The goal is to experiment with feature selection, expand the training dataset, and refine the classification process to achieve better performance.


1. **Dataset and Training Setup**:
   - Train my model on **at least 250 images** from the MNIST dataset and test it on a **test set of 60 images**.
   - Expand the dataset used in the original notebook to include more training samples.

2. **Feature Selection**:
   - Experiment with various filtration techniques and feature extraction methods, such as:
     - **Radial filtrations** with three different centers.
     - **Height filtrations** in two different directions.
   - Compute features like:
     - **Persistent Entropy**.
     - **Carlsson Coordinates**.
   - Concatenate all extracted features into a **single feature vector** for each image.

3. **Feature Engineering**:
   - Ensure that the length of your feature vector does not exceed **200 features**.
   - Save the list of features for each image as a **pickle file**.

4. **Model Selection**:
   - Choose a classifier for your task, such as:
     - A simple **Deep Neural Network (DNN)**.
     - A **Random Forest Classifier**.
   - Train your model on the processed dataset.

5. **Model Evaluation**:
   - Test your algorithm on a **test set** (images not used during training).
   - Evaluate and report the **accuracy** of your model.

## Goal
The primary objective is to improve the accuracy of the MNIST classification model through thoughtful feature engineering and classifier selection. Experiment with various feature extraction techniques and model architectures to achieve optimal results.
