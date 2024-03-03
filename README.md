# Scraping-and-Predictions-of-Politifact-website
Politifact's truth-o-meter website (https://www.politifact.com/truth-o-meter/) organizes statements by public figures into 5 categories: True, Mostly True, Half True, Mostly False, False, Pants on Fire.

Your first task is to create a Python Notebook called "Scraping.ipynb" that  collects all statements from the True, Mostly True, Mostly False, False, Pants on Fire categories. Ignore the Half True category.
Collect only the following information for each statement:

The date of the statement
The platform on which the statement was made (e.g. Twitter)
The text of the statement.
The name of the person who made the statement.
The deliverables of the first task are:

Scraping.ipynb
A 'data.csv' file  that includes the above information for all statements. The csv should include 1 row for each statement. Each row should have five columns: date,platform,text,person, truthfulness category. 
 

Your second task is to create a second python notebook called "Prediction.ipynb". This notebook should:
Read data.csv
Convert the  True and Mostly True labels to just True.
Convert the Mostly False, False, Pants on Fire labels to just False  
Split the data into two non-overlapping chunks: 70% used for training and 30% for testing.
Train a binary (True/False) classifier on the training set.
Print your classifier's accuracy on the testing set.
