# Player-Classifier
Built Classification models to determine the player from Shakespeare-plays dataset using Feature Engineering and exploratory data analysis.

# Problem Statement

## To be, or not to be
### Classy Shakespeare plays and players
1. Set up a data science project structure in a new git repository in your GitHub account
2. Download the Shakespeare plays dataset from https://www.kaggle.com/kingburrito666/shakespeare-plays
3. Load the data set into panda data frames
4. Formulate one or two ideas on how feature engineering would help the data set to establish additional value using exploratory data analysis
5. Build one or more classification models to determine the player using the other columns as features
6. Document your process and results
7. Commit your notebook, source code, visualizations and other supporting files to the git repository in GitHub

---
## Data Description
### This is a dataset comprised of all of Shakespeare's plays. It includes the following:
- The first column is the Data-Line, it just keeps track of all the rows there are.
- The second column is the play that the lines are from.
- The third column is the actual line being spoken at any given time.
- The fourth column is the Act-Scene-Line from which any given line is from.
- The fifth column is the player who is saying any given line.
- The sixth column is the line being spoken.

## What are we doing?
- Train Classification models to predict Player from Shakespeare plays dataset.
- Explore Shakespeare plays dataset
- Using Feature Engineering, transform data to provide best accuracy with classification models.
- Use different Models to identify the best one for this dataset.

## Analysis
#### This is number of players in each play plot
![](https://github.com/SFLazarus/Player-Classifier/blob/master/reports/Number_of_players_vs_play.png)
### After exploring dataset we understood the availability of huge data for each play helps build more accurate model
#### This is a play count plot- to determine how many attributes we have for each play
![](https://github.com/SFLazarus/Player-Classifier/blob/master/reports/play_count_plot.png)
### Also our main goal is to determine player from dataset.
#### This plot is for player count- to determine how many attributes we have for each player

![](https://github.com/SFLazarus/Player-Classifier/blob/master/reports/player_count_plot.png)

---
# Results: (80% of data is used for training and 20% for testing)

### Decision Tree Classifier
#### Accuracy of Decision Tree classifier on training set: 100%
#### Accuracy of Decision Tree classifier on test set: 79%
- performed pretty good compared to others.

### K- Nearest Neighbors Classifier
#### Accuracy of K-NN classifier on training set: 76%
#### Accuracy of K-NN classifier on test set: 53%
-not too bad performance.

### Gaussian Naive Bayes Classifier
#### Accuracy of GNB classifier on training set: 23%
#### Accuracy of GNB classifier on test set: 22%
- worst performance overall.

### Random Forest Classifier
#### Accuracy of Random Forest classifier on training set: 100%
#### Accuracy of Random Forest classifier on test set: 82%
- best performing model.

---

# Project Structure:
### Readme.md
- Project description
### Data
- Contains raw data in csv format
### Notebooks
- Jupyter Notebook for Exploratory data analysis, Visualization, Feature Engineering and Classification.
### Reports
- plot- number of players vs play 
- Plot- Play count
- Plot- Player count
### Requirements.txt
- Info about Tools, frameworks and libraries required to reproduce the work flow
