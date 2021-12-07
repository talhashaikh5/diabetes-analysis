# Analysis on diabetes

## Table of Contents
1. [Installation](#Installation)
2. [Motivation](#Motivation)
3. [File Descriptions](#FileDescriptions)
4. [Results](#Results)
5. [Licensing, Authors and Acknowledgment](#Licensing,AuthorsandAcknowledgment)

## Installation
To run this project, I used Python 3 and installed the following libraries: pandas and matplotlip.

## Motivation
As part of my Udacity Nanodegree in Data Science, I ran an exploratory analysis on diabetes dataset of 520 people to help myself understand more about the medical issues faced by diabetes paitents. The questions that my analysis are aimed at answering are the following:
- Most affected age group?
- Most common issues in males with respect to their age?
- Most common issues in females with respect to their age?

### Most affected age group?
By summing up the people with diabetes I was able to understand which group of people are most affected. I divided people into age groups of 10-20, 20-30, 30-40, 40-50, 50-60, 60-70 and above 70,
then by plotting the graph of the data it was very clear that which groups were most affected.

### Most common issues in males?
After collecting and analyzing data I found that there are a few medical issues that are linearly correlated to the age group of males namely "weakness", "irritability", "partial_paresis", "muscle_stiffness" but these issues are not co-related to the age of females.

### Most common issues in females?
Issues found in males are not co-related to the issues in females. The most common issues found in females with respect to age are "visual_blurring", "itching", "genital_thrush".

## File Descriptions
My analysis can be found in this [file](https://github.com/talhashaikh5/diabetes-analysis/blob/main/diabetes.ipynb). This Jupyter notebook demonstrates all the related work to answer the questions above. It includes the preprocessing steps required to analyze diabetes datasets. Additionally, it includes all the visualizations used to answer these questions. 

## Results
You can find my results in this Medium [post](https://medium.com/@talha.shaikh5/3-things-you-should-know-about-diabetes-3b9b7acb4420).


## Licensing, Authors, and Acknowledgment
All data were retrieved from Kaggle. You can find the datasets for [diabetes](https://www.kaggle.com/andrewmvd/early-diabetes-classification) here.
