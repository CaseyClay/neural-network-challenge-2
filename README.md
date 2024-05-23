# neural-network-challenge-2
UNC Chapel Hill & UNC Charlotte AI Bootcamp Module 19 Challenge

### Background
You are tasked with creating a neural network that HR can use to predict whether employees are likely to leave the company. Additionally, HR believes that some employees may be better suited to other departments, so you are also asked to predict the department that best fits each employee. These two columns should be predicted using a branched neural network.

### Files
The attrition jupyter notebook starter code was provided. The creation of neural network was done by me. 

### Functions/Dependencies
from sklearn.model_selection import train_test_split
from sklearn.preprocessing import StandardScaler, OneHotEncoder
from pandas as pd
from numpy as np
from tensorflow.keras.models import Model
from tesnorflow.keras import layers
