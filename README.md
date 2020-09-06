## Selected Topic
Airline flight delays in 2015.

# Reason for selection
The airline industry is close to $900 billion in size worldwide as of 2019, with flight delays costing the industry $8 billion annually. Being able to predict which factors influence delays and by how many minutes, is the question airlines have been struggling to answer since their inception.

## Description of source data
This dataset provides information on the flights in 2015. Data includes the date of the flight, the airline, flight and tail number, the origin and destination airport, the times and distance associated with the flights as well as the reason for delay and if the flight was cancelled or diverted. With 31 columns and so much data, we will remove certain columns to clean the dataset. Those columns include the year because all this data is only for 2015. We will also remove the cancellation reason column because 98% of the values are null. As well, we will remove all the flights that were cancelled as it does not provide us with any data on factors that could’ve influence delay and we will remove the whole cancelled column as well.

## Question 
Which factors influence flight delays, and by how many minutes? 

# Technologies Used
## Data Cleaning and Analysis
Pandas will be used to create a DataFrame, clean the data, and perform exploratory analysis. Additional analysis will be completed using Python.

## Database Storage
Postgres is the database we intend to use, and we will use pgAdmin to display the data. 

## Machine Learning
SciKitLearn is the ML library we will be using to create a classifier. Our training and testing setup will ideally be divided by 80% and 20%, respectively. 

## Dashboard
Tableau will be used to visualize our results and create a story answering our question. 
