# Phase_1-Project-Moringa
## Introduction
Microsoft want to get into the movie business and would like to understand how to create movies and kind of films that are currently doing well at the box office.

## Objectives
To be able to create a list of films that are doing better at the box office

## Exploratory Data Analysis 

## Unzip the 3 datasets
Unzip the 3 datasets to have them into .csv formats

### Import packages
First import the required packages that are required, import pandas, matplotlib.pyplot and os

import the 3 datasets in python

```python
#import the 3 datasets
# bom.movie_gross - dataset
df_bom = pd.read_csv("zippedData/bom.movie_gross.csv")
# imdb.title.ratings - dataset
df_rating = pd.read_csv("zippedData/title.ratings.csv")
# imdb.title.basics - dataset
df_basics = pd.read_csv("zippedData/title.basics.csv")
```
# Working with Bom movie Dataset
# Access the first 5 cases
df_bom.head()

# Access the first 5 cases
df_bom.head()

# Access the lat 5 cases
df_bom.tail()


# Description of the number of columns and rows in the dataset 
print("The bom movie dataset has",df_bom.shape[0], "rows and",df_bom.shape[1],"columns.")

# Access the features and overview of the data
df_bom.info()


# Number of missing per variable in the dataset
df_bom.isna().sum()

# Recommendations

* Microsoft should consider investing in BV and Wb studios as they are the top two selling studios
* To invest domestically, they should put more focus on the BV studios
* To acquire more market spaces, they should aim a rating of between 6-8 scores as the average rating is approximately 7
