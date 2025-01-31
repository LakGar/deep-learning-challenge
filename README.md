# Deep Learning Challenge - Alphabet Soup Charity Analysis

## Overview
This project builds a **binary classification model** using **TensorFlow/Keras** to predict whether funding applicants for Alphabet Soup will be successful.

## Steps
1. **Preprocess the Data**
   - Load and clean the dataset.
   - Drop unnecessary columns (`EIN`, `NAME`).
   - One-hot encode categorical variables.
   - Scale numerical features using `StandardScaler()`.

2. **Build and Train the Model**
   - Create a neural network using **TensorFlow/Keras**.
   - Add hidden layers with activation functions.
   - Train and evaluate the model.
   - Save the trained model as `AlphabetSoupCharity.h5`.

3. **Optimize the Model**
   - Improve accuracy (>75%) by adjusting:
     - Number of neurons and layers.
     - Activation functions.
     - Training epochs.
   - Save the optimized model as `AlphabetSoupCharity_Optimization.h5`.

4. **Write a Report**
   - Explain preprocessing steps.
   - Justify model architecture.
   - Document optimization attempts.
   - Suggest alternative models.

## Files
- `AlphabetSoupCharity.ipynb` - Main notebook for preprocessing and training.
- `AlphabetSoupCharity_Optimization.ipynb` - Notebook for model optimization.
- `AlphabetSoupCharity.h5` - Trained model file.
- `AlphabetSoupCharity_Optimization.h5` - Optimized model file.
- `README.md` - Project documentation.

## Tools Used
- **Python**
- **Pandas & Scikit-Learn** (Data preprocessing)
- **TensorFlow/Keras** (Neural network model)
- **Google Colab/Jupyter Notebook**

## Submission
- All files are uploaded to the **Deep Learning Challenge** GitHub repository.
