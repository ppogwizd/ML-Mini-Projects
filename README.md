# ML-Mini-Projects

This repository contains mini projects related to machine learning, developed as part of the "Python for Data Science and Machine Learning Bootcamp" course on Udemy.

## Table of Contents

- [Introduction](#introduction)
- [Project Structure](#project-structure)
- [Technologies](#technologies)
- [Installation](#installation)
- [Usage](#usage)

## Introduction

The `ML-Mini-Projects` repository includes a collection of Jupyter notebooks demonstrating various machine learning algorithms and techniques. Each notebook corresponds to a different machine learning project covered in the Udemy course "Python for Data Science and Machine Learning Bootcamp."

## Project Structure

The repository is organized into the following folders:

1. **Linear Regression**
    - [`ML_Ecommerce_company.ipynb`](https://github.com/ppogwizd/ML-Mini-Projects/blob/main/1%20-%20Linear%20Regression/ML_Ecommerce_company.ipynb): A project demonstrating linear regression on e-commerce data.
    
2. **Logistic Regression**
    - [`ML-Titanic.ipynb`](https://github.com/ppogwizd/ML-Mini-Projects/blob/main/2%20-%20Logistic%20Regression/ML-Titanic.ipynb): A project utilizing logistic regression to predict Titanic survival rates.
    
3. **K Nearest Neighbors**
    - [`KNN.ipynb`](https://github.com/ppogwizd/ML-Mini-Projects/blob/main/3%20-%20K%20Nearest%20Neighbors/KNN.ipynb): A project showcasing the K Nearest Neighbors algorithm.
    
4. **Decision Trees and Random Forests**
    - [`DT _RF_Loans_Project.ipynb`](https://github.com/ppogwizd/ML-Mini-Projects/blob/main/4%20-%20Decision%20Trees%20and%20Random%20Forests/DT%20_RF_Loans_Project.ipynb): A project applying decision trees and random forests to a loans dataset.
    
5. **Support Vector Machines**
    - [`SVM_Iris_project.ipynb`](https://github.com/ppogwizd/ML-Mini-Projects/blob/main/5%20-%20Support%20Vector%20Machines/SVM_Iris_project.ipynb): A project using support vector machines on the Iris dataset.
    
6. **K Means**
    - [`K Means Clustering Project.ipynb`](https://github.com/ppogwizd/ML-Mini-Projects/blob/main/6%20-%20K%20Means/K%20Means%20Clustering%20Project.ipynb): A project demonstrating K Means clustering.

7. **Natural Language Processing**
    - [`Spam_Detector_Project.ipynb`](https://github.com/ppogwizd/ML-Mini-Projects/blob/main/7%20-%20Natural%20Language%20Processing/Spam%20detector/Spam_Detector_Project.ipynb): A project demonstrating natural language processing for spam detection.
    - [`Yelp_Reviews_Classifier.ipynb`](https://github.com/ppogwizd/ML-Mini-Projects/blob/main/7%20-%20Natural%20Language%20Processing/Yelp%20Reviews%20classifier/Yelp_Reviews_Classifier.ipynb): A project classifying Yelp reviews using natural language processing techniques.
      
8. **Neural Nets and Deep Learning**
    - [8 - Neural Nets and Deep Learning](https://github.com/ppogwizd/ML-Mini-Projects/tree/main/8%20-%20Neural%20Nets%20and%20Deep%20Learning): This section delves into the exploration and implementation of neural networks and deep learning models, showcasing their applications and functionalities within machine learning projects.


## Technologies

- **Python**: The primary language used for implementing the machine learning algorithms.
- **Jupyter Notebook**: An interactive environment for running the code and visualizing the results.
- **Various Python Libraries**: Including but not limited to `numpy`, `pandas`, `scikit-learn`, `tensorflow`, `matplotlib`, and `seaborn`.

## Installation

To run the notebooks, you need to have Python and Jupyter Notebook installed on your machine. Follow these steps to set up the environment:

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/ML-Mini-Projects.git
    cd ML-Mini-Projects
    ```

2. Install the required libraries:
    ```bash
    pip install -U scikit-learn
    ```
    or
    ```bash
    conda install scikit-learn
    ```
3. For Natural Language Processing you need to install the `nltk` library and download the `stopwords` package:
    ```bash
    pip install nltk
    ```
    After installing `nltk`, you need to download the `stopwords` package. You can do this by running the following commands in a Python environment:
    ```python
    import nltk
    nltk.download('stopwords')
    ```
4. For Neural Nets and Deep Learning you need to install the `tensorflow` library:
    ```bash
    pip install tensorflow
    ```

## Usage

Open the desired Jupyter notebook to explore the corresponding machine learning project. You can launch Jupyter Notebook from the command line:

```bash
jupyter notebook
