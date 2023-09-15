# Analyzing Stroke Data - Data Science Python Project in Jupyter Notebook
## Project Overview:
This project focuses on using Python to explore and analyze stroke prediction data, with the goal of answering the following questions:
* What percentage of individuals in the dataset have had a stroke?
* What is the mean age for males and females to have had a stroke?
* What is the greatest risk factor for having had a stroke between hypertension, smoking, and heart disease?
* What percentage of individuals with strokes have a combination of hypertension, smoking, and heart disease?
* What is the difference in stroke rates between individuals over 65 who live in urban areas vs. those who live in rural areas?

The project code and results are contained in the Jupyter Notebook stroke-data-independent-project.ipynb, along with a summary below.

## Data:
The dataset for this project can be found across two files:
* healthcare-dataset-stroke-data.csv contains the original dataset downloaded from Kaggle, used to predict whether a patient is likely to have a stroke based on parameters such as gender, age, comorbidities, and smoking status.
* stroke-data-independent-project.ipynb contains the Python code created with Jupyter Notebook.

Credit: The dataset was sourced from Kaggle using the following link:
* https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset

My thanks go out to the dataset author for releasing this data into the public domain.

## Conclusion:
This project provided useful insight into the risk factors for stroke. The findings are as follows:
* Only 4.9% of the patients in the total dataset have suffered a stroke.
* The mean age for males and females to have had a stroke is very close, with males being 68.5 years of age and females being 67.1 years of age.
* When examining the predisposing conditions of all individuals who have had a stroke, 45% of those with a history of smoking have suffered a stroke, indicating that smoking has a higher risk factor for stroke compared to hypertension (26.5%) and heart disease (18.9%).
* Individuals with a combination of all three risk factors (hypertension, heart disease, and smoking history) make up 14.5% of all individuals who have suffered a stroke.
* Individuals living in urban areas have a 5.6% higher rate of stroke patients than those living in rural areas.

Some questions that can't be answered by the dataset include:
* How can factors such as access to healthcare, race, socioeconomic status, education, and stress be used to further enhance the stroke prediction data?
* How can selective revelation or suppression of information have affected the data?

## Python Versions and Library Dependencies:
* Python 3.11.4
* Pandas 1.5.3
