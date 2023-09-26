# Dissertation-project - Exploring the Performance of Crime Prediction Using Machine Learning Approaches
Final-year Computer Science degree project involving code and dissertation. A first-class grade was received for this final project.

## Outline
For my final-year project, I created a software artefact in Google Colab to compare the performance of four different machine learning models in predicting crime. The models used were:
*  Naive Bayes
*  Decision Tree
*  Random Forest
*  K-Nearest Neighbours

Hyperparameter Tuning and K-Fold Cross-Validation were also implemented to measure the differences they could make in the evaluation metrics' scores and their impact on each model's performance.

## Files
### Dissertation_v3.pdf (*Dissertation*)
The full write-up report of around 11,950 words. I encourage anyone to have a read; a lot of time and effort was put in and I am sure you will learn something from it.

### crimeReducedLabels.csv
An early version of a crime dataset downloaded from Kaggle (https://www.kaggle.com/datasets/ankkur13/boston-crime-data#) with unnecessary features removed and unnecessary labels (classes) removed. Ten classes are in this dataset. This file is used in 'DataCleaner.ipynb' and goes through multiple phases of data cleaning to create a usable dataset.

### crimeNoErrorEqual_3.csv
An altered version of 'crimeReducedLabels.csv' with NAN values removed, erroneous values renamed, and an equal number of entries for each class. The number of classes has been reduced from ten to three.

### DataCleaner.ipynb
A Jupyter-style Notebook developed in Google Colab which takes the file 'crimeReducedLables' as input and outputs a cleaner, more usable version without erroneous values. Follow each step to clean the data.

### DataAnalysis(sklearn_v2).ipynb
The main software artefact. Another notebook which was developed in Google Colab including all the necessary libraries, functions, code - to allow a full running of each model and each variant - and results. A great discussion of the whole process and reasoning is written up in the dissertation.
