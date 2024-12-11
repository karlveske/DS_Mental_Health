This is the final project of the University of Tartu Data Science course. 

## Achievements
In this project, we analyzed patterns and differences between people who have and don't have depression. 

And built an ML depression prediction model, which achieved a prediction accuracy of ~93% in a Kaggle competition. This means that, on that competition dataset, our model correctly classified 93% of the cases as depressed or not depressed.

The score we achieved in the [Kaggle competition](https://www.kaggle.com/competitions/playground-series-s4e11/data?select=train.csv)
![image](https://github.com/user-attachments/assets/bf648532-71b6-4b38-96d0-82f3f14dc038)

## The project consists of the following components. 
- Depression_Analysis Jupyter notebook -  exploratory analysis and visualizations of the data.
- train_cleaning & test_cleaning Jupyter notebooks - these are notebooks where one-hot encoded Kaggle data. 
- Data_Preparation Jupyter notebook - this further alters the train_cleaner2.csv dataset to be more suitable for ML and splits it up into four new datasets. 
- Predictive_Modelling Jupyter notebook - this is the notebook where the RandomForest ML model is created. 


### Data

Raw data: (inside a separate directory)
- train.csv and test.csv. This was the data we got from Kaggle, cleaned (deleted rows with broken or missing values) and one-hot encoded for the data analysis and ML.
- There are some other working files we used in our work that can be ignored.  

Working data:

This is the data we used for analysis and ML. 
- test_cleaner2.csv
- train_cleaner2.csv

Data generated from <I> Data_Preparation </I> Jupyter notebook and what's used inside <I> Predictive_Modelling </I> Jupyter notebook 
- X_train_sub.csv
- X_val.csv
- y_train_sub.csv
- y_val.csv

#### Authors:
Karl-Christofer Veske

Kristjan Siim

Karl Tomasson
