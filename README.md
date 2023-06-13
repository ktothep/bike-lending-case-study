# bike-lending-case-study
Upgrad Bike Lending Case Study

Problem Statement
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.


A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 


In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.


They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

Which variables are significant in predicting the demand for shared bikes.
How well those variables describe the bike demands
Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 


Business Goal:
You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.

Approach Taken
 
 - Data was analysed to view any Null values are present or not in the columns or if any row if containing more than required null values.
 - Categorical variables were mapped to the original values mentioned in the data dictionary.
 - EDA was perfomed to view relationship between different variables and target variable.
 - Encoding was performed to get dummy variables from catgorical variables. 
 - Data was splitted in ratio 70:30 to get training and test data.
 - Linear Regression Model was created using statsmodel API.
 - Mixed approach was used for feature elimination.We used RFE and manual process.
 - 5 models were created after column removal. 
 - Model was then fitted on test dataset

R2 Value

- Training Dataset 0.84
- Test Dataset 0.81
