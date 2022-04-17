# Predicting Super Bowl Champions

## Project Overview

This repository is our attempt to build a model to predict Super Bowl champions. We used NFL data from 2002 till 2021 seasons to make our predictions. Our goal is to build a model with at least 50% accuracy.
    
## Methodology

### Data Cleaning/Munging

We aggreggated NFL game data for each team by year. We aggregated on the following features:

    * Passes Completed
    * Passes Attempted
    * Passing Yards
    * Rushing Yards
    * Rushing Attempts
    * Fumbles
    * Interceptions
    * Drives
    * First Downs
    * Defensive/Special Teams TDs
    * Third Downs Completed
    * Third Downs Attempted
    * Fourth Downs Completed
    * Fourth Downs Attempted
    * Sacks Count
    * Sacks Yards Lost
    * Penalties Count
    * Penalties Yards Lost
    * Time of Possession (in seconds)
    * Points Scored
    * Wins
    
After aggregation, we combined all years' data and indicated whether the team won the Super Bowl. This indication became our target prediction.  

### Dataset Considerations

Once we aggregated the raw data, our output gave us a dataset with each teams' full season statistics. Of course, in one season there can only be one winner. This dataset can be classified as an imbalanced dataset. Roughly 3% of the data is Super Bowl winners, while the rest are not. In an ideal situation, the distribution between target and non-target data points should be even or close to even. 

### Model Considerations

Because we are making a binary prediction, we used the following models:

    * model 1
    * model 2
    * model 3
    
We used model 1 because xyz

We used model 2 because abc

We used model 3 because def

## Results

### Model 1 Analysis

Model 1 achieved a score of xyz

### Model 2 Analysis

Model 2 achieved a score of abc

### Model 3 Analysis

Model 3 achieved a score of def

## Dashboard

To visualize our data, we created a dashboard that allows you to compare, in each year, the super bowl winner vs. non-super bowl winners.  

Additionally, we created a dashboard that, using our best performing model, allows you to input the features listed above to predict the score of such a team winning the super bowl. We believe this tool will allow teams to set achievable targets to maximize their chances to win a Super Bowl
