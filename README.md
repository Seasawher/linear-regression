# Linear Regression Health Costs Calculator

In this challenge, you will predict healthcare costs using a regression algorithm.

You are given a dataset that contains information about different people including their healthcare costs. Use the data to predict healthcare costs based on new data.

## Specifications

* Make sure to convert categorical data to numbers. 

* Use 80% of the data as the `train_dataset` and 20% of the data as the `test_dataset`.

* pop off the "expenses" column from these datasets to create new datasets called `train_labels` and `test_labels`. 

* To pass the challenge, `model.evaluate` must return a Mean Absolute Error of under 3500. This means it predicts health care costs correctly within $3500.
