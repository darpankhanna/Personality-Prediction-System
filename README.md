# Personality-Prediction-System

 Use of data mining concepts and python data science libraries for simple demostration to analyse and classify personalities of a given set of people or an individual.
 
 # Abstract 
 
The project uses learning algorithms and advanced data mining concepts to mine user characteristics data and learn from the patterns. This project will come across areas where it has access to large amounts of person behavioral data. This data can be helpful to classify persons using Automated personality prediction and classification. There are areas where there is access to large amounts of person behavioral data. This data can help us classify persons using automated personality classification.
 
 # Approach 
 
Five characteristics of different individuals commonly known as big five characteristics namely, openness, neuroticism, conscientiousness, agreeableness and extraversion are stored in a dataset and used for training. Based on this training, the personality of individuals are predicted using data mining concepts. Before testing the dataset, it is pre-processed using different data mining concepts like handling missing values, data discretization, normalisation etc.This pre-processed data can then be used to classify/predict user personality based on past classifications. The system analyses user characteristics and behaviors. System then predicts new user personality based on personality data stored by classification of previous user data.
Model used to predict test dataset is “Logistic Regression” because Logistic regression is an effective model to predict output class labels for dependent categorical data.

# DataSet Description 
Attribute Description: No. of attributes are 7 as listed below.
S.NO | Attribute | Type | Range 
-----|-----------|------|------
1|Gender	|nominal|	Male / Female
2|Age|	numeric	|17-28
3|Neuroticism	|numeric|	1-8
4|Openness	|numeric|	1-8
5	|Agreeableness	|numeric|	1-8
6	|Conscientiousness|	numeric	|1-8
7|	extraversion	|numeric	|1-8

# Use instructions:
1. Clone the repository
2. On command line, enter 'pip install scikit-learn'
3. Make sure train.csv follows the guidelines we use. Example training has been provided in said file.
4. Run the file 'code.py'

# File information:
● Code.ipynb has the general overview of the project
● code.py contains all the code for the project
● output.csv will contain where the output after you run the file
● train.csv contains the learning set for the project.  This will show the progress of the machine learning
● test.csv is used for the prediction that the model set uses.

# Overview:
Example data can be found in 'train.csv' as well as 'Code.ipynb.' The predictions will be saved into output.csv which officially has what you would find.  The biggest directory is the main directory as other folders are not as important for this case.

# Contribution Guideline information:
We welcome anyone to contribute to this project.  In order to contribuite, we ask that you view CONTRIBUTING.md for further information.

# Acknowledgements:
We acknoledge the following libraries which make this possible:

sklearn library

# Class label description:

No. of class labels: 5

Type: Nominal

Values: 
● Extraverted
● Serious 
● Responsible 
● Lively
● dependable
