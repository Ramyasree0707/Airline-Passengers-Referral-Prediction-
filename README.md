# Airline-Passengers-Referral-Prediction


The main objective of this project is to create a model that can predict whether a traveller will recommend his or her flight to their family,friends and the public.

**Problem Statement**
Data includes airline reviews from 2006 to 2019 for popular airlines around the world with multiple choice and free text questions. Data is scraped in Spring 2019. The main objective is to predict whether passengers will refer the airline to their friends.

**Description of Features**

   airline: Name of the airline.
   
   overall: Overall rating given to the trip on a scale of 1 to 10.
   
   author: Author of the trip.
   
   reviewdate: Date of the review.
   
   customer review: Review of the customers in free text format.
   
   aircraft: Type of the aircraft.
   
   travellertype: Type of traveler (e.g., business, leisure).
   
   cabin: Cabin on the flight.
   
   date flown: Flight date.
   
   seatcomfort: Rated between 1-5.
   
   cabin service: Rated between 1-5.
   
   foodbev: Rated between 1-5.
   
   entertainment: Rated between 1-5.
   
   groundservice: Rated between 1-5.
   
   valueformoney: Rated between 1-5.
   
   recommended: Binary target variable (0 or 1).

**Data Preparation**
   1. Dropping rows with entirely missing values.
   2. Dropping columns that do not add value for analysis.
   3. Removing duplicates.
      
****Exploratory Data Analysis (EDA)**

EDA helps us gain insights into the data, detect errors, understand data patterns, and identify relationships between variables. Some key findings from EDA include:

1. Relationship between traveler types and ratings.
2. Relationship between cabin and ratings.
3. Distribution of ratings.
4. Correlation between variables.

**Feature Engineering & Data Pre-processing**

1. Handling missing values and imputing missing values using the median and mode.
2. Categorical encoding using One-Hot encoding.
3. Handling Multicollinearity.

**Model Building**

We implemented the following machine learning models:

1. Logistic Regression
2. Random Forest Classifier
3. Support Vector Machine

**Conclusion**
In this project, we conducted a comprehensive analysis to predict airline passenger referrals. We explored the dataset, built and evaluated multiple machine learning models, and selected the Support Vector Machine (SVM) model with hyperparameter tuning as our final prediction model due to its high accuracy. The project's insights can assist airlines in understanding passenger preferences and optimizing their services to enhance customer satisfaction and referrals.
