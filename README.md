# Neural_Network_Charity_Analysis

# Overview 
Machine Learning Algorithms have been applied to create a binary classifier capable of predicting whether applicants will be successful if it is funded by an ordinary soup company. One employee recieved a CSV file containing more than 34,000 organizations that have recieved funding from this company over the years. The tools to conduct this analysis is using Google Colab that inherits the Python Pandas Programming Language along with various libraries relating to Machine Learning, which will be presented in this report. 


# Results 
There are two parts to cosider when applying machine learning to make predictions using the CSV file. 

The first part of this report is using Data Processing to analyze the data presented in the CSV file in further detail. Using Google Colab, and the Scikit-Learn's function, StandardScaler(), the data is preprocessed in order to compile, train, and evaluate the neural network model applied during this analysis. To clean the data, the columns EIN, and NAME were removed since these columns held no value to the mdoel. The variables that were considered for this model were STATUS, ASK_AMT, IS_SUCESSFUL, APPLICATION_TYPE, CLASSIFICATION, USE_CASE, ORGANIZATION, INCOME_AMT. USE_CASE_Other, and AFFLIATION_Other were the columns that were not considered. The dependent variable is IS_SUCESSFUL, since this is the value the model is predicting with high accuracy. 

The second part is compiling, training, and evaluating the model. This yields four attempts to compiling, training, and evaluating the model.

From the first attempt, two hidden layers were applied, one of which has 80 Neurons (Layer One), and the second one has 30 Neurons (Layer Two). The model used Relu, and Sidmoid Activations Function becuase Sigmoid functions are best used to summarize binary classification problems whereas relu functions are used for non-linear datasets. The columns USE_CASE_Other and AFFLIATION_Other were removed. 
