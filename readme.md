# Recommender Systems Project 2 

Department of Mathematics and Computer Science, Adam Mickiewicz University, 2021

Authors: Klaudia Kandulska and Piotr Zioło

## Project description

The main goal of the project was to code a recommender based on a neural network model, then tune and evaluate it. The recommender results are compare to the results with AmazonRecommender and NetflixRecommender on HR@10 metric. The project use MLPClassifier from sklearn library to fit and compute the results.

## The project constists of 
### two Jupyter notebooks:
project_1_data_preparation.ipynb - notebook with data preparation(copied from the 1st project),
project_2_recommender_and_evaluation.ipynb - the main notebook for this project
### data preprocessing code:
data_preprocessing/data_preprocessing_toolkit.py,
data_preprocessing/dataset_specification.py.py,
data_preprocessing/people_identifier.py.py
### and data:
data/hotel_data/hotel_data_original.csv.

## Preparing your computer
To be able to run this project you will need:
- Anaconda with python v.3.8(or higher)
- Numpy
- Pandas
- matplotlib.pyplot
- seaborn
- IPython.display
- torch
- livelossplot
- sklearn
- random
- hyperopt
- traceback
- os
