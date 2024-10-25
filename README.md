# Project Title: Fac Recognition Usisng Deep Learning and Machine Learning Model 

## Overview:
This project focuses on comparing Convolutional Neural Network (CNN) and Support Vector Machine (SVM) models in terms of performance on a dataset. The steps include data preprocessing, model building, fine-tuning, and evaluation on both validation and test sets.

## Table of Contents:
1. **Problem Definition and Proposed Solution**
2. **Data Preprocessing**
    - Reshaping Data
    - Converting to One-Hot Encoding
    - Normalizing Input
    - Data Augmentation
3. **Modeling**
    - **CNN:**
        - Build Baseline Model
        - Fine-tune Model
    - **SVM:**
        - Build Base Model
        - Model Tuning
4. **Model Evaluation**
    - Validation Test
    - Test Set Evaluation
5. **Conclusion**

## Dependencies:
- Python 3.x
- TensorFlow
- scikit-learn
- NumPy
- Pandas

## Instructions:
1. **Problem Definition and Proposed Solution**: This section describes the objective of the project, which is to apply machine learning techniques for model comparison and to propose the best performing solution.
   
2. **Import Library and Dataset**: Import necessary libraries and load the dataset for the analysis.

3. **Data Preprocessing**: 
   - Reshape the data for model input.
   - Convert categorical labels into one-hot encoding format.
   - Normalize the input data for better model performance.
   - Apply data augmentation techniques to increase the dataset's variability and prevent overfitting.

4. **Modeling**:
   - **CNN**: Build and fine-tune the Convolutional Neural Network model.
   - **SVM**: Build and tune the Support Vector Machine model for comparison.

5. **Model Evaluation**: Evaluate both models on the validation and test sets to determine their effectiveness.

6. **Conclusion**: Summarize the results, indicating which model performed better based on accuracy and loss metrics.

