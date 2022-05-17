# BoomBike-Sharing_Multiple-Linear-Regression
# Problem Statement :
A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.  In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.  Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:  a-Which variables are significant in predicting the demand for shared bikes? b-How well those variables describe the bike demands ?
# Business Goal :
We need to build a model that explains the demand for shared bikes with the available independent variables and to understand how exactly the demands vary with different features. In future, the company, accordingly, can manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for the company management to understand the demand dynamics of a new market.
# Steps to follow :
- Read and Understand the data
- Clean the dataset (if needed)
- Visualising the data
- Data Preparation
- Splitting the data into Training and Testing dataset
- Building and Training Linear Models
- Residual Analysis of the Train Data
- Making Predictions using the Final model
- Evaluating the model
# Algorithm :
• Read and Understand the data:-
   - Import necessary libraries, check info, shape and statistical description of
     dataset
• Clean the dataset (if needed):-
   - Convert the data type if needed, check for null and duplicate values
   - Drop the columns which are unnecessary
• Visualizing the data:-
   - Pair plot among numerical variables
   - Box plot among categorical variables
   - Heat map for an idea of the correlation again the target variable
• Data Preparation:-
   - Create dummy variables for the categorical features with more than two levels
• Splitting the data into Training and Testing dataset and Scaling:-
   - Split the entire data set in 70:30 ratio for train and test respectively
   - Also, scale all the features using MinMaxScaler and compress the range
     between 0 and 1
• Building and Training Linear Models:-
   - Assign y_train and X_train
   - Perform RFE to only keep the most important 15 features
   - Add coefficient constant to train data
   - Build the model with significant p-values and VIF
• Residual Analysis and Evaluation of the Train Data:-
   - Calculate the residual
   - Plot error terms on distribution plot to check if it is a normal distribution or not
   - Plot error terms on scatter plot to check the constant variance
• Making Predictions using the Final model:-
   - Scale the test data as we did before
   - Assign y_test and X-test using final model features
• Residual Analysis and Evaluation of the Test Data
   - Calculate residual
   - Calculate r-squared, adj. r-squared, mean squared error
   - Compare them with our train data values
   - Plot the error terms on distribution plot and scatter plot
   - Also check y_test vs. y_pred on a scatter plot
• Conclusion:-
   - Conclude your findings and recommendations.
