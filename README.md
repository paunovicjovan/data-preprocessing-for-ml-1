# Data Preprocessing for Machine Learning

This repository contains a seminar paper and an accompanying Jupyter Notebook developed for the course **Data Collection and Preprocessing for Machine Learning**, as part of the MSc program in Artificial Intelligence and Machine Learning at the University of Niš, Faculty of Electronic Engineering.

## Project Overview

The objective of this project is to provide a systematic overview of key data preprocessing techniques used in machine learning, along with a practical demonstration of their impact on model performance.

The theoretical part covers:

- The need for data transformation  
- Feature scaling techniques (Min-Max, Standardization, Robust, Max-Abs)  
- Normalization  
- Distribution transformations (Log, Box-Cox, Yeo-Johnson, Quantile, etc.)  
- Encoding of categorical attributes (One-Hot, Ordinal, Target, Binary, etc.)  
- Discretization methods  
- Handling extreme values (detection and treatment)  
- Feature construction  

## Practical Implementation

All preprocessing techniques described in the paper are demonstrated in a Jupyter Notebook using the [**Bank Marketing dataset**](https://www.kaggle.com/datasets/janiobachmann/bank-marketing-dataset).

The task is a binary classification problem. Model performance is evaluated using:

- Logistic Regression  
- Random Forest  
- Support Vector Machine (RBF kernel)  

Each preprocessing approach is compared against baseline results to analyze its influence on classification performance.

## Repository Structure

- `Teorijski deo/` - Seminar paper (theoretical background)
- `Prakticni deo/` - Jupyter Notebook with experiments and model evaluation

## Technologies Used

- Python  
- NumPy  
- Pandas  
- Scikit-learn  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

This project connects theoretical foundations of data preprocessing with practical experimentation in a real-world classification setting.