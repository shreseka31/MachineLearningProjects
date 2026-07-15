# MachineLearningProjects
SII Prediction Project:
# Adolescent Internet Use Severity Predictor

This project is a Python-based desktop application that uses machine learning to predict an adolescent’s **Severity Impairment Index (SII)** based on data from the **Child Mind Institute**.

## Overview

The application is designed to help parents and guardians better understand how internet use may be affecting their child. Users complete a questionnaire containing 23 inputs, including:

* Physical and demographic attributes
* Sleep-related information
* Responses about the parent’s perception of their child’s internet use
* Behavioral and lifestyle factors

After the questionnaire is completed, the application processes the responses and generates a predicted SII score.

## Machine Learning Model

The prediction model was developed using a **Random Forest Classifier**. The original dataset was cleaned and preprocessed, and the 23 features with the strongest correlations to SII were selected for training.

Through feature selection, data preprocessing, and model refinement, the model achieved approximately **95% prediction accuracy** on the evaluated dataset.

## Application Interface

The user interface was created with **Tkinter** and provides a simple, quiz-style experience. Parents or guardians can answer each question within the application and receive an SII prediction after submitting their responses.

## Technologies Used

* Python
* Pandas
* Scikit-learn
* Random Forest Classifier
* Tkinter
* Child Mind Institute dataset

## Purpose

This project demonstrates how machine learning and accessible user-interface design can be combined to transform behavioral-health data into an interactive and informative tool.

## Disclaimer

This application is intended for educational and research purposes only. Its predictions should not be considered a medical diagnosis or a substitute for advice from a qualified healthcare professional.

