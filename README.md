# mental_health_in_tech
## Project Overview
This project explores mental health in technology-related jobs, with the aim of supporting an HR pre-emptive program to mitigate mental health issues. The data is derived from a survey conducted among technology-oriented employees and includes responses related to mental health conditions and workplace environments.
## The dataset 

## Goal
The main goal is to:

- Wrangle and preprocess the data to handle missing values and categorical variables.
- Apply clustering techniques to categorize survey participants based on their responses.
- Visualize and interpret the clusters to help identify potential points of leverage for HR interventions aimed at improving mental health at the workplace.
## Steps and Approach
- Data Preprocessing: Handled missing values, performed feature encoding, and reduced dimensionality using PCA.
- Clustering: Used K-Means clustering on principal components to categorize participants, evaluated using silhouette scores.
- Analysis of Clusters: Visualized and analyzed key features contributing to each cluster, examining both numerical and categorical data.
- Visualization: Created plots to showcase cluster characteristics, such as job role frequencies, and other significant features.

## Requirements
The project is implemented in Python. The following libraries are required:
> pandas
> numpy
> scikit-learn
> matplotlib

You can install all dependencies with:
```console
pip install -r requirements.txt
```
## Running the code 
#### 1. Clone the repository
```console
git clone https://github.com/wojtek-chanas/mental_health_in_tech.git
```
#### 2. Navigate to the project directory
```console
cd mental-health-in-tech-jobs
```
#### 3. Open and run the main notebook or script to reproduce the analysis.
#### 4. Outputs will include cluster visualizations, tables of key insights, and the top features contributing to mental health conditions in the surveyed employees.

