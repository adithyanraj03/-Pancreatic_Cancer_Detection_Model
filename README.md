<h1>Pancreatic Cancer Detection Model</h1>
This repository contains a Python notebook for a pancreatic cancer detection model. The dataset used in this project is sourced from the open-access paper published on December 10, 2020: Link to Paper

Dataset Information
Dataset Name: Debernardi et al 2020 data.csv
Number of Patients: 590
Healthy controls: 183
Patients with non-cancerous pancreatic conditions (e.g., chronic pancreatitis): 208
Patients with pancreatic cancer: 199
Author
Author: Adithya N Raj
Date: 27-02-2024 10:15:02
Overview
The goal of this project is to predict which patients have pancreatic cancer based on various features extracted from the dataset.
![download](https://github.com/adithyanraj03/-Pancreatic_Cancer_Detection_Model/assets/39313793/3487bbff-799f-4f13-a800-4a35fa0b5ed0)


Code Overview
The Python notebook utilizes various libraries such as NumPy, Pandas, Matplotlib, Seaborn, and scikit-learn. It consists of the following key sections:

1. Data Loading and Preprocessing
Data is loaded from the provided CSV file (Debernardi-et-al-2020-data.csv).
Columns are selected, and categorical variables are transformed for analysis.
2. Exploratory Data Analysis (EDA)
A pair plot is created to visualize relationships between features, especially concerning the diagnosis.
Correlation matrix is plotted to identify relationships between variables.
3. Random Forest Classifier
A pipeline is created for a Random Forest Classifier.
Grid search is performed over different hyperparameters to find the best model.
Feature importances are plotted.
4. XGBoost Classifier
Another pipeline is created for an XGBoost Classifier.
Similar to Random Forest, a grid search is performed over hyperparameters.
Classification report and balanced accuracy are printed.
Feature importances are plotted.
5. Model Comparison
XGBoost is identified as the best-performing model with an accuracy of 0.8766.
Instructions for Use
Download the dataset from the provided link and save it as Debernardi-et-al-2020-data.csv.
Run the provided Python notebook to execute the analysis and model building.
Explore the visualizations and model performance metrics.
Feel free to contribute, provide feedback, or use this code as a basis for further research in pancreatic cancer detection. If you have any questions or suggestions, please don't hesitate to reach out.
