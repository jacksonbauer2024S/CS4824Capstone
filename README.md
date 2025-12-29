# Modeling and Forecasting the Spread of the Spotted Lanternfly in the United States Using Machine Learning

### Author
Jackson Bauer  


## Overview
This project applies machine learning to model and predict the spread of the Spotted Lanternfly across the United States.  
Using citizen science data from EDDMapS, environmental features, and spatial lag features, the models attempts to identify the counties most at risk to infestation.


## Methods and Models
- **Environmental Model:** Uses Tree of Heaven presence and urbanization features with no location features
- **Coordinates Model:** Uses latitude and longitude with environmental features.
- **Spatial Model:** Uses infested neighbors and environmental features.
- **Evaluation Metrics:** AUC, Precision, Recall, and F1-score


## Instructions 

Jupyter Notebooks can be found in the Notebooks directory.
Notebooks should be ran in this order:
1. data_cleaning.ipynb
2. feature_engineering.ipynb
3. ml_model.ipynb


## Data Access

The datasets used in this project are too large to store directly in this repository.  
They are available for download via Google Drive:

**[Access Data Here](https://drive.google.com/drive/folders/1JfZAyMrxdpIDJ9Sw70aXtkf0S6_948iu?usp=sharing)**

The data folder should be extracted and placed in the main project directory.








