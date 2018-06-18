---
title: My R Package
author: Abigail Radey
date: '2018-06-18'
slug: my-r-package
categories: []
tags: []
---

	Emiliana Delgado and I created a function called train_test that splits data into a training and testing set.
It takes in a csv file from the current R project folder in quotes (ex: "file_name.csv"), the train set percentage, and the test set percentage. The function reads the csv file and creates a train and test set from the specified percentages. The output is a list where the first index returns the training set and the second index refers to the testing set. 
Example of naming train and test set after running: data <- train_test("train_copy.csv", 0.7, 0.3), train <- data[1], test <- data[2].