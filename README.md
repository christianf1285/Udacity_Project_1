# Udacity_Project_1

### Motivation
Within this project we will further analyze the StackOverflow surveys between 2011-2019. By using different techniques of data wrangling and manipulation we will try wo answer the following business questions:

1. Can we find any trend over time related to the participants and their employment?
2. Which programming languages are most popular? Are there any significant changes over time?
3. Which kind of developers are highest paid among the participants in the 2019 survey?
4. What are the top features which have most impact on salary in the 2019 survey?

### File description
In the repository we have all survey files as .csv downloaded from the Stackoverflow site. In order to simplify data loading process files were renamed to have a consistent naming convention ('<year> Stack Overflow Survey Results.csv'). Beside the input files there is one Jupyter Notebook file with all code used for the analysis including comments.

Due to the file size of the surveys they are stored in the following google drive:
https://drive.google.com/drive/folders/15jDCyU3hkk1bMK0RV_nrA8ZtmU5AT7dD?usp=sharing

Please note that you adjust the folder variable accordingly according to where you store the files in your working directory.
  
### Python libraries used
The following imports are required in order to execute all functions in the notebook:
- import numpy as np
- import pandas as pd
- import os
- from os import listdir
- from os.path import isfile, join
- import re
- import matplotlib.pyplot as plt
- from sklearn.ensemble import RandomForestRegressor
- from sklearn.model_selection import train_test_split
- from sklearn.preprocessing import LabelEncoder
- from sklearn.metrics import r2_score, mean_squared_error
