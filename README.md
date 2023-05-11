# Neural_Network_Charity_Analysis
1.	Overview of the analysis:
•	The purpose of this analysis is to help Beks create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.
•	By using deep-learning Neural Networks, Beks can determine which charities are likely to be a success donation.
2.	Results:
 Data Preprocessing
•	The variable that is considered the target for the model is the 'IS_SUCCESSFUL’. 
•	The variables that are considered to be the features for the are model 'APPLICATION_TYPE', 'CLASSIFICATION', 'USE_CASE', 'ORGANIZATION', 'STATUS', 'INCOME_AMT', 'SPECIAL_CONSIDERATIONS', and 'ASK_AMT'.
•	The variables that are neither targets nor features and were removed from the input data are EIN' and 'NAME'.
Compiling, Training, and Evaluating the Model
I used 16,10,10 as far as the numbers of neurons with 3 layers and the activations functions were “relu” and “sigmoid”
 image.png
 image.png
 
•	To increase the performance of the model, I doubled the number of neurons and added layers, but the model accuracy increased just a little bit.
 
image.png

3.	Summary:
•	In summary, the deep learning model has a better accuracy score compared to the other models. I found that in deep learning model the accuracy score is better optimized when using less hidden years. The more is not always the merrier, so my recommendation is to be cautious when deciding how many hidden layers or even the number of neurons to use.

