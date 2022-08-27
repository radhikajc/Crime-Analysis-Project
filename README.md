# Analysis of Crime Data across the United States:

# Aim of the Project:

# Data Source:

The FBI collects crime data through the Uniform Crime Reporting (UCR) Program, of which NIBRS is a part, is a city, county, state, and Federal law enforcement program.The data sourced for this project is from law enforcement agencies submitting 12 months of NIBRS data to the FBI UCR Program for 2012 and were converted and published in CIUS, 2012.

# Data cleaning & Exploratory Data Analysis:

As part of this project, we looked into our data and made the following changes in order to get clean data for our model. The following changes were made:
a. Unmerge rows and fill NA values with the values of the previous row respectively. 
b. Replace special characters and spaces.
c. Drop variables with higher correlation.

<img width="1049" alt="image" src="https://user-images.githubusercontent.com/103969912/187014253-918f7f85-b910-4715-9f3a-e5a0918f1f53.png">


In order to understand the data set better, we performed a series of exploratory data analysis and visualised these to obtain the trends.
a. Obtained the top 5 states with highest number of Assault offenses registered in all the agency types except cities.
<img width="255" alt="image" src="https://user-images.githubusercontent.com/103969912/187014173-831b99be-2ae5-495f-9b0e-bc06e1ca838b.png">

b. Explored the category of crimes that were most registered in universities.

c. Compared offenses at Michigan State University to offenses at all other universities.
<img width="527" alt="image" src="https://user-images.githubusercontent.com/103969912/187014190-064ecdcf-ed6e-43d8-90c0-c72d334ffea4.png">

d. Which provinces have state agencies with lowest number of digital offenses registered.
<img width="670" alt="image" src="https://user-images.githubusercontent.com/103969912/187014204-74fa0a97-15a3-4a56-ae61-28b98954dba0.png">

e. Which category of agency type and their respective agency names have the highest number of offenses registered per million people.
<img width="219" alt="image" src="https://user-images.githubusercontent.com/103969912/187014215-efbf585d-663c-49e3-b853-344d8d68401e.png">

f. Plotted a Geospatial visualization of the data showing the offence type with highest number of offences in that province.

<img width="1440" alt="image" src="https://user-images.githubusercontent.com/103969912/187013749-0a372aa3-f18a-45dc-ad44-0a304e320abe.png">


# Data modelling: 

Data: 
X: Population, Drug/Narcotic Offenses, Drug/Narcotic Violations, Drug Equipment Violations, Theft from Building, Theft from Coin-operated Machine, Theft from Motor Vehicle, Theft of Motor Vehicle Parts or Accessories. 
Y: Total number of offenses
Task: - Implemented Linear regression and Random forest model. 
- Used feature engineering to derive new features from columns in X.
- Implemented Statistical model from data available to predict total number of offenses.
Analysis: Is linear regression model able to fit the above data well? 
What type of linear regression model performed the best? 


