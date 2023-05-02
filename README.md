This is my personal repository for ISM6251- Data Science Programming.

This repository has all my assignments organized in a weekly folder structure.
  
  # ISM6251-DSP

DETAILED DESCRIPTION :

This group of Data Science Programming concepts focused on trying varied machine modeling techniques and using from Logistic Regression, Decision Trees, Neural Networks, Text Mining, DNN, RNN , Neural Networks, Ensemble Techniques to SVM. 



1.WEO1-DATA PREP ASSIGNMENT :

Here we identified five categorical variables. We encoded two of these variables (neighborhood_cleansed and property_type) using dummy variable encoding and the remaining three using label encoding (room_type, bed_type, and cancellation_policy). For this exercise, we solved a situation where our manager disagrees with your choice of encoding and wants the variables you encoded using dummy variable encoding to use one-hot-encoding instead. He also wants one of the three variables (the cancellation_policy variable) you label encoded to be one-hot-encoded.




2.ICP02 Regression :

For this exercise, we added to the notebook an "early stop" approach to fitting the polynomial (and concatenate this result to the rmses dataframe).



3.WE02-Regression:

Here we created two notebooks on model-generating and model-fitting. In the first copy, I have increased the amount of noise added to the data in the data-generating notebook. Have Runned the model fitting notebook on this new data. Added a markdown cell at the end of the notebook that discusses how the resulting model fit results and how these compare to the original.In the second copy, I have decreased the number of observations generated in the data-generating notebook. Runned the model fitting notebook on this new data. Added a markdown cell at the end of the notebook that discusses how this resulting model fits results and how these compare to the original.




4.ICP03 SVM:
Analyzed the SVM models used in the SVM example (svm with linear kernel, svm with rbv kernel, and svm with poly kernel). measured models' Accuracy, Precision, Recall, and F1 results to your performance data frame. 

5.WE03-SVM:
Utilized SVM classification and the three kernels, measured the scores to find the winning model.


6.ICP04 Decision Trees:
Applied Decision tree model using the random search/gridsearch to the data from data from airbnb with a target of price_gte_150.

7.WE04-Universal Bank:
Universal bank has recently tried a marketing campaign to sell their new CD account product to existing customers. They contacted 5000 of their non-CD account customers with an offer. The data provided in universal.csv is the result of this market test. Used the techniques covered in this class to load and clean the data. Then, identified the best predictive model (using only the models covered thus far: Logistic Regression, SVM (with various kernels), and Decision trees). With the target variable being CD Account and the scoring measure is recall. Used RandomSearchCV combined with GridSearchCV to identify the best parameters for each model tested.


8.Assignment-Erythematous.1.1 &1.2:
Found a unique dataset and choosed recall score as scoring metric based on the business problem and fitted a logistic regression, an SVM, and a decision tree model for modeling and used random and grid searches to test a range of parameter values for each model. Logistic regression was best for our data.

9.ICA06 Text Mining:
Made use of lemmatization techniques to group those words 












