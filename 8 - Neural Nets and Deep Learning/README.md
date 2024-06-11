## Project Overview

This project aims to build a predictive model that determines whether a customer will be able to repay a loan based on their input data. The project is structured into three main sections:

1. **Exploratory Data Analysis (EDA)**
2. **Data Preprocessing**
3. **Model Evaluation and Performance**

The model leverages neural networks and deep learning techniques using technologies such as TensorFlow, Keras, Pandas, NumPy, Seaborn, and Matplotlib. The project is implemented in Python using Jupyter Notebook.

## Repository Structure

- `Loan-payback-predict-model.ipynb`: The Jupyter Notebook containing the entire project.
- `lending_club_info.csv`: CSV file containing descriptions of the columns in the dataset.
- `lending_club_loan.csv`: CSV file containing the loan data.
- `README.md`: This file.

## Sections Breakdown

### Section 1: Exploratory Data Analysis (EDA)

**Goal:** Gain an understanding of which variables are important, view summary statistics, and visualize the data.

- Load and explore the dataset.
- Generate summary statistics for numerical features.
- Visualize the distribution of important features using histograms, box plots, and correlation matrices.
- Identify any patterns or trends that could influence the model's predictions.

### Section 2: Data Preprocessing

**Goals:** Clean the data by removing or filling any missing values, eliminate unnecessary or repetitive features, and convert categorical string features into dummy variables.

- Handle missing data by either removing or imputing values.
- Drop redundant or non-informative features.
- Encode categorical variables using techniques like one-hot encoding.
- Normalize or standardize numerical features to improve model performance.

### Section 3: Model Evaluation and Performance

**Goals:** Build, train, and evaluate the neural network model using deep learning techniques.

- Split the data into training and testing sets.
- Construct a neural network using TensorFlow and Keras.
- Compile the model and specify loss functions, optimizers, and metrics.
- Train the model on the training data.
- Evaluate the model's performance on the test data using appropriate metrics (e.g., accuracy, precision, recall, F1-score).
- Visualize the model's performance using confusion matrices, ROC curves, and other relevant plots.

## Technologies Used

- **Python**: Programming language.
- **Jupyter Notebook**: Interactive notebook environment.
- **TensorFlow & Keras**: Deep learning frameworks.
- **Pandas**: Data manipulation and analysis.
- **NumPy**: Numerical computing.
- **Seaborn & Matplotlib**: Data visualization.
