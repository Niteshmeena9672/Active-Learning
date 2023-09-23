# Iris Dataset Active Learning with Support Vector Machines (SVM)

This project demonstrates Active Learning with Support Vector Machines (SVM) using the famous Iris dataset. Active Learning is an iterative machine learning process that selects the most informative data points for labeling, reducing the need for extensive manual labeling.

## Description

In this project, we utilize the Iris dataset, which contains measurements of petal length and width for three species of iris flowers (Iris-setosa, Iris-versicolor, and Iris-virginica). We perform Active Learning to iteratively train an SVM classifier on this dataset, selecting the most ambiguous data points for labeling in each iteration. The process is visualized with a series of plots and saved as a GIF.

## Prerequisites

Before running the code, make sure you have the following Python libraries installed:

- scikit-learn
- pandas
- numpy
- matplotlib
- imageio

You can install them using pip:

```bash
pip install scikit-learn pandas numpy matplotlib imageio
