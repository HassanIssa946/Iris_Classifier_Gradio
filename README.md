# Iris Species Classifier

This project provides a web interface for predicting the species of Iris flowers using different machine learning classifiers.We have tarined diffeerent ML classidfication methods and compared between them.then we implemented an interface built using Gradio and allows users to input various flower measurements to receive a prediction.

## Table of Contents

- [Overview](#overview)
- [Installation](#installation)
- [Usage](#usage)
- [Model Details](#model-details)
- [Features](#features)
- [Contributing](#contributing)
- [License](#license)


### Confusion Matrices: **SVM:** - **Naïve Bayes:**  - **KNN:**


## Overview

The Iris Species Classifier project aims to provide an easy-to-use web interface for predicting the species of Iris flowers using different classifiers including Support Vector Machine (SVM), Naïve Bayes, and K-Nearest Neighbors (KNN). The prediction is made using a model trained on the Iris dataset.In this project you will see the diffeerence between the accurracy of the classifiers with respect to this dataset.

## Installation

To run this project locally, follow these steps:

1. **Clone the repository:**

    ```sh
    git clone https://github.com/your-username/Iris_Species_Classifier.git
    cd Iris_Species_Classifier
    ```

2. **Create a virtual environment:**

    ```sh
    python -m venv venv
    # On macOS/Linux
    source venv/bin/activate  
    # On Windows
    venv\Scripts\activate
    ```

3. **Install the required packages:**

    ```sh
    pip install -r requirements.txt
    ```

4. **Download the dataset:**

    Place your `IRIS.csv` file in the project directory.

## Usage

    To run the Gradio interface, execute the following command:

    ```sh
    python app.py

## Model Details

The project includes three classifiers: Support Vector Machine (SVM), Naïve Bayes, and K-Nearest Neighbors (KNN). Each classifier is trained on the Iris dataset, and their performance is evaluated using confusion matrices.

### Differences in Classifier Concepts

- **Support Vector Machine (SVM):**  
  SVM is a supervised machine learning algorithm which can be used for both classification or regression challenges. It performs classification by finding the hyperplane that best divides a dataset into classes. It is effective in high dimensional spaces and is memory efficient.

- **Naïve Bayes:**  
  Naïve Bayes classifiers are a collection of classification algorithms based on Bayes’ Theorem. It is not a single algorithm but a family of algorithms where all of them share a common principle, i.e., every pair of features being classified is independent of each other. It works well with small datasets and is simple and fast.

- **K-Nearest Neighbors (KNN):**  
  KNN is a simple, easy-to-implement supervised machine learning algorithm that can be used to solve both classification and regression problems. KNN works by finding the distances between a query and all the examples in the data, selecting the specified number of examples (K) closest to the query, then votes for the most frequent label (in the case of classification) or averages the labels (in the case of regression).

  ## Features

- **Interactive Web Interface:** Allows users to input flower measurements and select a classifier to get a prediction.
- **Multiple Classifiers:** Includes SVM, Naïve Bayes, and KNN classifiers.
- **Handles Missing Data:** Automatically fills missing data with column means.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.
