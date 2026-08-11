# Hospital Length of Stay Prediction Using Machine Learning

## Project Overview

Hospital Length of Stay (LOS) is an important factor in healthcare management. Predicting the expected duration of a patient's hospital stay can help with resource planning, bed management, and operational decision-making.

This project applies machine learning techniques to predict hospital length-of-stay categories using patient and hospital-related data. The project covers the complete machine learning workflow, including data preprocessing, exploratory data analysis, feature engineering, feature selection, model training, evaluation, and prediction.

## Objectives

* Analyze patient and hospital-related data.
* Perform data preprocessing and exploratory data analysis.
* Identify relevant features associated with hospital length of stay.
* Apply feature engineering and feature selection techniques.
* Develop machine learning classification models.
* Compare model performance.
* Predict length-of-stay categories for unseen patient records.

## Technologies Used

| Category                | Technologies            |
| ----------------------- | ----------------------- |
| Programming Language    | Python                  |
| Data Processing         | Pandas, NumPy           |
| Machine Learning        | Scikit-learn            |
| Models                  | Random Forest, LightGBM |
| Data Visualization      | Matplotlib, Seaborn     |
| Development Environment | Jupyter Notebook        |

## Machine Learning Approach

The project follows a structured machine learning workflow:

**Data Preprocessing → Exploratory Data Analysis → Feature Engineering → Feature Selection → Model Training → Model Evaluation → Prediction**

### 1. Data Preprocessing

The dataset was prepared for machine learning by performing the required preprocessing steps. Patient and hospital-related attributes were cleaned and transformed into a suitable format for model training.

### 2. Exploratory Data Analysis

Exploratory Data Analysis (EDA) was performed to understand the structure and distribution of the data. The relationships between different features and hospital length-of-stay categories were analyzed to identify useful patterns.

### 3. Feature Engineering

Feature engineering was performed to prepare relevant input variables for the machine learning models. Appropriate transformations and preparation of the available features helped the models learn meaningful patterns from the data.

### 4. Feature Selection

Feature selection was performed to identify relevant features that contribute to predicting hospital length of stay. This helped reduce unnecessary information and provided the models with more useful input variables.

## Machine Learning Models

Two tree-based machine learning algorithms were used in the project:

### Random Forest

Random Forest is an ensemble learning algorithm that combines multiple decision trees to produce a final classification result.

Each decision tree learns patterns from the training data, and the predictions from the individual trees are combined to make the final prediction. This approach allows Random Forest to capture complex relationships between patient-related features and hospital length-of-stay categories.

In this project, Random Forest was used to classify patients into different length-of-stay categories based on the selected features.

### LightGBM

LightGBM (Light Gradient Boosting Machine) is a gradient boosting framework designed for efficient and high-performance machine learning on structured and tabular datasets.

Unlike Random Forest, where multiple trees are generally built independently, LightGBM builds trees sequentially. Each new tree focuses on improving the errors made by previous trees, allowing the model to progressively learn patterns from the data.

LightGBM was used as another classification approach for predicting hospital length-of-stay categories and evaluating its effectiveness on the healthcare dataset.

## Model Training and Prediction

After preprocessing and feature selection, the prepared dataset was provided to the machine learning models for training.

The models learned relationships between the selected patient and hospital-related features and the corresponding length-of-stay categories.

After training, the models were used to generate predictions for patient records that were not used during the prediction process.

## Model Performance

The developed machine learning approach achieved:

**Training Accuracy: 99.87%**

This indicates that the trained model was able to correctly classify approximately **99.87% of the records in the training dataset**.

The high training accuracy demonstrates that the model was able to learn the patterns present in the training data effectively.

However, training accuracy alone does not measure how well a model generalizes to completely unseen data. A separate test dataset or cross-validation would provide a more reliable estimate of real-world model performance.

## Key Contributions

* Performed data preprocessing and data preparation.
* Conducted exploratory data analysis to understand the dataset.
* Implemented feature engineering techniques.
* Performed feature selection to identify relevant variables.
* Developed classification models using Random Forest and LightGBM.
* Trained and evaluated the machine learning models.
* Generated predictions for unseen patient records.
* Analyzed model performance and prediction results.

## Dataset

The project uses healthcare-related patient and hospital information to predict different hospital length-of-stay categories.

The original dataset is not included in this repository to avoid sharing potentially sensitive healthcare information.

## Results and Outcome

The project successfully demonstrates the application of machine learning to hospital length-of-stay prediction.

The combination of data preprocessing, feature engineering, feature selection, and tree-based machine learning algorithms enabled the models to learn patterns from patient and hospital-related information.

The developed model achieved **99.87% accuracy on the training dataset**, demonstrating strong performance on the data used for model training.

## Project Information

**Project Type:** Academic Project
**Domain:** Healthcare / Machine Learning
**Programming Language:** Python
**Development Environment:** Jupyter Notebook
**Machine Learning Models:** Random Forest, LightGBM
**Training Accuracy:** 99.87%
