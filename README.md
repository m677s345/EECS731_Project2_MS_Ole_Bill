# EECS731_Project2_MS_Ole_Bill

The assignment for this project are as follows:

Classy Shakespeare plays and players
Set up a data science project structure in a new git repository in your GitHub account
Download the Shakespeare plays dataset from https://www.kaggle.com/kingburrito666/shakespeare-plays
Load the data set into panda data frames
Formulate one or two ideas on how feature engineering would help the data set to establish additional value using exploratory data analysis
Build one or more classification models to determine the player using the other columns as features
Document your process and results
Commit your notebook, source code, visualizations and other supporting files to the git repository in GitHub

Through this project we were required to use information provided in the shakespeare plays dataset such as the play, lines, and line numbers to determine the identity of the player who said those lines. 

I began with some exploratory data analysis to get an idea of what features could be useful in assigning players to their lines. I chose line number broken into act scene and line as well as the neame of the play as my features. 

I then began exploring different classification models to train and test. I found that the Decision tree classifier and the Random forest classifier did much better than the naive Bayes model at an accuracy of 70 percent vs 31 percent. I found that the decision tree classifier was much faster and less computationally expencive than the random forest classifier with little difference in accuracy.
