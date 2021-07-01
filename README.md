# Offer-Complete
Predict offer completeness with Starbucks data
Installation
Libraries used are :
-pandas as pd
-numpy as np
-math
-json
-seaborn
-matplotlib
-pandas
-sklearn

Project Motivation :

With the given datasets and background information provided, I am interested in exploring the following with the Starbucks dataset for this Capstone project: 
• Predict the response to an offer - If the consumer will complete an offer or not?
• Measure the accuracy of the model, precision, and F1-Score 
• Explore which input parameters/features play a critical role in predicting whether the customer will take the offer or not.
#Strategy

We will use data wrangling techniques to clean the data,and perform necessary conversion of columns to suitable data types
We will use statistics and visualizations as needed to help us understand the 3 datasets profile,portfolio,and transcript better
We will use 3 models Logistic Regression as the base model, Random Forest and Decision Tree classifiers as the additional models to predict if a particular offer will be completed by the customer or not.

Project Descriptions :
• Loading and exploring the data - The datasets will be loaded, and some exploratory analysis will be performed in this stage such as reviewing the distribution of data, number, and type of features 
- Dimensions of the dataset - Statistical summary of attributes
- Data visualization with histograms on input variables to get idea on their distribution 
• Data preprocessing and feature engineering:
  - Data cleansing and feature engineering will be performed in this stage
  - From the transaction data set, I intend on creating additional attributes based on existing to study their impact on offer completion.
  Examples could include since how long the user has been a member, # of offers received by a user, # of times the offer has converted to a buy and so on. 
  • Splitting the data into train/test sets - We will split the data into training and test data sets and derive test/train features and labels 
  • Modeling - Defining and training a Decision Tree and Random Forest binary classifiers
  • Making improvements on the model - This will be an incremental step. We will adjust the input parameters/features that feed the model to improve the accuracy rate as applicable.
  - We will perform model tuning to optimize the metrics we are interested in
  • Evaluating and comparing model test performance - We will measure the accuracy, precision, recall and F1-Score for both our models and suggest the better model for predicting an Offer to be completed

Files Descriptions:

The data is contained in three files:

portfolio.json - containing offer ids and meta data about each offer (duration, type, etc.)
profile.json - demographic data for each customer
transcript.json - records for transactions, offers received, offers viewed, and offers completed

portfolio.json

id (string) - offer id
offer_type (string) - type of offer ie BOGO, discount, informational
difficulty (int) - minimum required spend to complete an offer
reward (int) - reward given for completing an offer
duration (int) - time for offer to be open, in days
channels (list of strings)
profile.json

age (int) - age of the customer
became_member_on (int) - date when customer created an app account
gender (str) - gender of the customer (note some entries contain 'O' for other rather than M or F)
id (str) - customer id
income (float) - customer's income
transcript.json

event (str) - record description (ie transaction, offer received, offer viewed, etc.)
person (str) - customer id
time (int) - time in hours since start of test. The data begins at time t=0
value - (dict of strings) - either an offer id or transaction amount depending on the record

Acknowledgements:
Thank you to Udacity for providing the simulated Starbucks data files

Output Visuals :



Conclusion
