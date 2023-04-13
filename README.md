# ILLNESS-INSIGHT
The Illness Insight is a disease prediction system that uses machine learning algorithms to analyse and interpret a patient's medical history to predict the likelihood of developing a certain disease.

https://manikandan-0303-illness-insight-mdps-public-t077j9.streamlit.app/

# Project Structure:
The project has the following structure:
The 'dataset' folder contains the dataset files for each disease, which are in CSV format.
The 'collab file' folder contains Jupyter notebooks for data exploration, data preprocessing, and model building for each disease prediction.
The 'saved models' folder contains trained machine learning models for each disease prediction.
The 'multiple disease pred.py' file contains the code for the Streamlit application.

# Data:
The project uses publicly available datasets from various sources.

# Notebooks:
The Jupyter notebooks are organized as follows:

'heart-disease-prediction.ipynb' - This notebook contains the code for data exploration, data preprocessing, and model building for Heart disease prediction.

'parkinson-disease-prediction.ipynb' - This notebook contains the code for data exploration, data preprocessing, and model building for Parkinson's disease prediction.

'diabetes-prediction.ipynb' - This notebook contains the code for data exploration, data preprocessing, and model building for Diabetes prediction.

# Models:
The trained machine learning models are saved in the 'saved models' folder. These models can be used to predict whether a patient is affected by a particular disease.

# Requirements:
The project requires the following packages to be installed:
pandas
numpy
matplotlib
seaborn
scikit-learn
SVM
Logistic regression

# Instructions to run the code:
Install the required packages.
Run the notebook cells in order to reproduce the data preprocessing and model building process.
To make predictions using the trained models, load the respective model from the 'models' folder and use it to predict whether a patient is affected by a particular disease.
Run the Streamlit application by executing the following command in the terminal:
streamlit run app.py
The application will open in a web browser, allowing users to input patient data and view the predicted disease outcome.
