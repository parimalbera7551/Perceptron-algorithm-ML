# Perceptron Binary Classification
Overview
This project implements a Perceptron algorithm for binary classification tasks. The Perceptron is a type of linear classifier used for binary classification problems. This project demonstrates its application on both annotated data and randomly generated data.

# Objectives
Implement the Perceptron algorithm to classify data into two categories.
Visualize decision boundaries for both annotated and randomly generated datasets.
#Files
annotated_points_np_200.csv: A CSV file containing annotated data points used for training and testing the Perceptron.
# Usage
# Annoted Points
Run the gui_inputs.py Script:

This script allows you to manually annotate points for two linearly separable classes using a graphical user interface.
You can input points by pressing keys corresponding to different classes and clicking on the plot. Press escape to finish the annotation process.
Save the Annotated Points:

After annotation, the points will be saved as a CSV file named annotated_points_np_<number_of_points>.csv.
This file will contain the coordinates and labels of the annotated points.
# Load the Data
The data is loaded from the CSV file into a NumPy array, and labels are adjusted where necessary.

# Perceptron Implementation
The perceptron function is defined to perform the training of the Perceptron algorithm. It updates weights iteratively based on the training data.

# Visualization
Decision boundaries are visualized for the annotated dataset.
Randomly generated data is also used to demonstrate the Perceptron's ability to classify and visualize decision boundaries.
# Results
The decision boundary for the annotated dataset is plotted, showing how the Perceptron separates the two classes.
Randomly generated data demonstrates the Perceptron's effectiveness in creating a linear decision boundary for synthetic data.
# Example Outputs
# Annotated Data
The visualization shows how the Perceptron algorithm classifies and separates two different classes using the decision boundary.

# Random Data
For randomly generated data, the Perceptron successfully identifies a decision boundary between two clusters of points.

# Code Explanation
# Perceptron Function
The perceptron function implements the Perceptron learning algorithm. It updates the weights and bias based on misclassified points until convergence or the maximum number of iterations is reached.

# Plotting Decision Boundaries
The plot_line function is used to visualize the decision boundary created by the Perceptron. It plots the line and data points to show how the Perceptron separates the classes.
