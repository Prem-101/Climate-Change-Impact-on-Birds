# Climate Change Impact on Birds

### Overview
This project leverages machine learning to predict climatic conditions based on bird species and location, offering insights into the impact of climate change on bird populations. Using machine learning, we analyse bird species distribution and associated environmental factors like temperature, humidity, sky and wind.

### Introduction
Bird populations are sensitive to climatic shifts. This project focuses on predicting the climatic conditions, such as temperature and precipitation, for different bird species based on their geographic location. It is designed to help conservationists and researchers better understand the environmental challenges birds face due to climate change.

## Dataset
The dataset includes:
- **Bird Species Data**: Contains information about bird species sighted across different geographic locations.
- **Location Data**: National Parks corresponding to bird sightings.
- **Climate Data**: Historical records of climate variables like temperature, humidity, sky and wind.
  
### Sources:
- [eBird Database](https://ebird.org/home)
  
### Exploratory Data Analysis (EDA)
The EDA conducted provides insights into how climatic factors affect bird species distribution and behavior. Key findings include:
- **Bird Distribution**: The variation in species distribution across different climate conditions.
- **Climate Impact**: How temperature, precipitation, and humidity levels correlate with specific bird populations.

**Visualizations**:
- Heatmaps displaying correlations between bird sightings and climate variables.
- Scatter plots showing the spread of bird species across various climate zones.
- Seasonal trend analysis showing how bird populations fluctuate with climatic changes.

## Modeling Approach
The model predicts climate conditions (e.g., temperature, humidity) based on bird species and geographic location. Several machine learning algorithms were tested, including:
- Random Forest Regressor
- Gradient Boosting Regressor
- XGBoost

  ### Model Inputs:
- **Bird Species**: Categorical data representing the bird species.
- **Location (Latitude, Longitude)**: Numerical inputs for geographic location.
- **Season**: Added to capture seasonal variation in climate conditions.

### Performance Metrics:
- **Root Mean Squared Error (RMSE)**
- **Mean Absolute Error (MAE)**
- **R2 Score**

## Results
The **Random Forest Regressor** emerged as the best model based on performance metrics.

## Technologies Used
- **Languages**: Python
- **Libraries**: 
  - Data Processing: `pandas`, `numpy`
  - Visualization: `matplotlib`, `seaborn`
  - Machine Learning: `scikit-learn`, `xgboost`
- **Tools**: Jupyter Notebook, Google Colab

## How to Run the Project
### Prerequisites:
- Python 3.x
- Jupyter Notebook
- Install required libraries using:
  ```bash
  pip install -r requirements.txt
