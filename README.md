---
title: "README.md"
author: "Birendeep Singh"
date: "2024-11-29"
output: html_document
---
# Getting and Cleaning Data Course Project

This project demonstrates how to collect, work with, and clean a dataset. The final goal is to create a tidy dataset that can be used for further analysis.

## Files in the Repository

1. `run_analysis.R`: R script to process the dataset and create the tidy dataset.
2. `FinalData.txt`: The tidy dataset.
3. `CodeBook.md`: Describes the variables, data, and transformations.

## Steps in the Analysis

1. Download and unzip the dataset.
2. Merge the training and test datasets.
3. Extract measurements on the mean and standard deviation.
4. Replace activity codes with descriptive activity names.
5. Label the dataset with descriptive variable names.
6. Create a second tidy dataset with averages for each variable, grouped by subject and activity.

## How to Run the Script

1. Place the `run_analysis.R` script in your working directory.
2. Run the script using `source("run_analysis.R")`.
3. The tidy dataset `data.txt` will be created in your working directory.

