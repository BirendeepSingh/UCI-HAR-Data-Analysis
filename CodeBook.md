---
title: "CodeBook.md"
author: "Manya Verma"
date: "2024-11-15"
output: html_document
---
# CodeBook for Tidy Dataset

## Variables

- `subject`: Identifier for the subject (1–30).
- `activity`: Activity performed (e.g., WALKING, SITTING).
- Other columns: Average of measurements for mean and standard deviation, grouped by subject and activity.

## Data Source

- Original data: [UCI Machine Learning Repository](http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones)

## Transformations

1. Merged training and test datasets.
2. Extracted measurements on mean and standard deviation.
3. Used descriptive activity names.
4. Applied descriptive variable names.
5. Calculated averages grouped by subject and activity.
