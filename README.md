# Lung Cancer Detection Project

<p align="justify">This project builds a lung cancer detection model using various machine learning algorithms. It helps in early detection of lung cancer based on applicant attributes like alcohol consumption, smoking habits, chest pain, swallowing difficulty, etc. The project follows a complete workflow from data preprocessing to model evaluation, showcasing the implementation of different regression models and their performance.</p>

# Table of Contents

* [Overview](https://github.com/AnjusriKandi/Lung-Cancer-Detection?tab=readme-ov-file#overview)
* [Dataset](https://github.com/AnjusriKandi/Lung-Cancer-Detection?tab=readme-ov-file#dataset)
* [Workflow](https://github.com/AnjusriKandi/Lung-Cancer-Detection?tab=readme-ov-file#workflow)
* [Modeling](https://github.com/AnjusriKandi/Lung-Cancer-Detection?tab=readme-ov-file#modeling)
* [Results](https://github.com/AnjusriKandi/Lung-Cancer-Detection?tab=readme-ov-file#results)

# Overview

<p align="justify">This project aims to predict whether a person could be affected by lung cancer based on various attributes. The model takes factors such as alcohol consumption, smoking habits, chest pain, and more. It uses machine learning algorithms and evaluates their performance on a given dataset.</p>

# Dataset

* [Dataset from Kaggle](https://www.kaggle.com/code/ihabsherbiny/lung-cancer-detection/input)
  
The dataset used in this project contains the following attributes:

|Attributes                 |Description                                                                 |
|:---------------------------|:--------------------------------------------------------------------------|
|**Gender**                 |Male/Female                                                                 |
|**Age**                    |Age of the patient                                                          |
|**Smoking**                |Indicates if the patient smokes(YES = 2, NO = 1)                            |
|**Yellow Fingers**         |Indicates if the patient has yellow fingers (YES = 2, NO = 1)               |
|**Anxiety**                |Indicates if the patient experiences anxiety (YES = 2, NO = 1)              |
|**Peer Pressure**          |Indicates if the patient is under peer pressure (YES = 2, NO = 1)           |
|**Chronic Disease**        |Indicates if the patient has a chronic disease (YES = 2, NO = 1)            |
|**Fatigue**                |Indicates if the patient experiences fatigue (YES = 2, NO = 1)              |
|**Allergy**                |Indicates if the patient has allergies (YES = 2, NO = 1)                    |
|**Wheezing**               |Indicates if the patient experiences wheezing (YES = 2, NO = 1)             |
|**Alcohol**                |Indicates if the patient consumes alcohol (YES = 2, NO = 1)                 |
|**Coughing**               |Indicates if the patient experiences coughing (YES = 2, NO = 1)             |
|**Shortness of Breath**    |Indicates if the patient experiences shortness of breath (YES = 2, NO = 1)  |
|**Swallowing Difficulty**  |Indicates if the patient has difficulty swallowing (YES = 2, NO = 1)        |
|**Chest Pain**             |Indicates if the patient experiences chest pain (YES = 2, NO = 1)           |
|**Lung Cancer**            |Final diagnosis indicating presence of lung cancer (YES, NO)                |

# Workflow

The code will:
1. Load and preprocess the data.
2. Identify and delete duplicate values.
3. Handle missing values and encode variables.
4. Visualize the data.
5. Train the model.
6. Display performance metrics for each model.

# Modeling

The following models are evaluated in this project:
* Linear Regression
* Logistic Regression

# Results

* Best Model: Both **Linear Regression** model and **Logistic Regression** model has provided equal accuracy.
* Key Metrics: The final model's accuracy, confusion matrix, and classification report are provided in the code.
   
