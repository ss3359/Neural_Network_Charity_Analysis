# Neural_Network_Charity_Analysis

# Overview 
Machine Learning Algorithms have been applied to create a binary classifier capable of predicting whether applicants will be successful if it is funded by an ordinary soup company. One employee recieved a CSV file containing more than 34,000 organizations that have recieved funding from this company over the years. The tools to conduct this analysis is using Google Colab that inherits the Python Pandas Programming Language along with various libraries relating to Machine Learning, which will be presented in this report. 


# Results 
There are two parts to cosider when applying machine learning to make predictions using the CSV file. 

The first part of this report is using Data Processing to analyze the data presented in the CSV file in further detail. Using Google Colab, and the Scikit-Learn's function, StandardScaler(), the data is preprocessed in order to compile, train, and evaluate the neural network model applied during this analysis. To clean the data, the columns EIN, and NAME were removed since these columns held no value to the mdoel. The variables that were considered for this model were STATUS, ASK_AMT, IS_SUCESSFUL, APPLICATION_TYPE, CLASSIFICATION, USE_CASE, ORGANIZATION, INCOME_AMT. USE_CASE_Other, and AFFLIATION_Other were the columns that were not considered. The dependent variable is IS_SUCESSFUL, since this is the value the model is predicting with high accuracy. 

The second part is compiling, training, and evaluating the model. This yields four attempts to compiling, training, and evaluating the model.

For the first attempt, two hidden layers were applied, one of which has 80 Neurons (Layer One), and the second one has 30 Neurons (Layer Two). The model used Relu, and Sidmoid Activations Function becuase Sigmoid functions are best used to summarize binary classification problems whereas relu functions are used for non-linear datasets. The columns USE_CASE_Other and AFFLIATION_Other were removed. The results for the loss and accuracy is shown below.

<img width="1041" alt="Screen Shot 2022-10-26 at 1 07 47 PM" src="https://user-images.githubusercontent.com/104328106/198114889-f710c2ea-4fbb-4237-a39c-7a9d1873c2e5.png">


For the second attempt, three hidden layers were applied. The first layer has has 80 Neurons, 30 Neurons for the second layer, and 15 neurons for the third layer. The model used Relu, and Sidmoid Activations Function becuase Sigmoid functions are best used to summarize binary classification problems whereas relu functions are used for non-linear datasets. The columns USE_CASE_Other and AFFLIATION_Other were removed.  The results for the loss and accuracy is shown below.

<img width="914" alt="Screen Shot 2022-10-26 at 1 09 04 PM" src="https://user-images.githubusercontent.com/104328106/198115140-aa309608-fbde-4cf6-b6d1-90e2d425ac25.png">


For the third attempt, three hidden layers were applied. The first layer has has 80 Neurons, 30 Neurons for the second layer, and 10 neurons for the third layer. The model used Relu, and Sidmoid Activations Function becuase Sigmoid functions are best used to summarize binary classification problems whereas relu functions are used for non-linear datasets. This attempt reflects back to the oringinal dataset presented. The results for the loss and accuracy is shown below.

<img width="1062" alt="Screen Shot 2022-10-26 at 1 10 03 PM" src="https://user-images.githubusercontent.com/104328106/198115351-f0c299ab-7379-414d-92fd-7af739fb2364.png">



Lastly, for the fourth attempt, three hidden layers were applied. The first layer has has 80 Neurons, 30 Neurons for the second layer, and 15 neurons for the third layer. The model used Relu, and Sidmoid Activations Function becuase Sigmoid functions are best used to summarize binary classification problems whereas relu functions are used for non-linear datasets. These functions were reordered as well.  This attempt reflects back to the oringinal dataset presented. This attempt reflects back to the oringinal dataset presented. The results for the loss and accuracy is shown below.


<img width="1151" alt="Screen Shot 2022-10-26 at 1 10 33 PM" src="https://user-images.githubusercontent.com/104328106/198115461-138a9c3b-974c-4891-b9f4-e587c1f82cf0.png">

In order to achieve an accuracy rate more than 75%, significant changes to the activation functions and hidden layers were considered. However, the runtime to execute the files was longer than expected. 


# Summary 
The models presented had an accuracy of approximately 
