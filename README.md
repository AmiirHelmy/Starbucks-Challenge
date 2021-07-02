# Starbucks-Challenge
Analyzing Starbucks rewards mobile app's data to determine which demographic groups respond best to which offer type.
## Table of contents
* [Project Motivation](#project-motivation)
* [Repo's Files](#Repos-Files)
* [Required Packages](#required-packages)
* [Acknowledgements](#acknowledgements)
* [Results](#results)
* [Medium Post](#medium-post)


## Project Motivation:
In this project we will analyze and combine transaction, demographic and offer data from Starbucks' mobile app to determine whether or not to send an offer to a user, and specify the attributes that affects that decision.


## Repo's Files:
```
.
├── data
│   ├── portfolio.json #portfolio data
│   ├── profile.json # profile data
│   └── transcript.json # transcript data
├── Pics
│   ├── 1.png # Percision formula
│   ├── 2.png # Recall formula
│   ├── 3.png # Accuracy formula
│   └── 4.png # F1-score formula
├── README.md # This file
└── StarbucksChallenge.ipynb # Project's Notebook


```


## Required Packages:

- python3
- pandas
- sklearn
- numpy
- json
- matplotlib
- seaborn
- re
- datetime

## Acknowledgements:

- This project was done as a part of Udacity's Data Scientist Nanodegree.
- Data is from Starbucks.

## Results:

- The company should give more offers to Males since they have more completed offers.
- They should focus on Discount offers since they are the most common types.
- Offers 7 and 6 have the highest completion counts, so Starbucks should send these offers more frequently.
- Starbucks may choose to do further analysis to determine how user’s income affects purchases. (example: map users’ income into categories [low, medium, high] and low-income users get more offers).
