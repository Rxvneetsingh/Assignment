# Encoding Categorical Data Lab

## Project Overview

This project is a part of a data analytics course and focuses on exploring different techniques to convert categorical features into numerical representations. The lab demonstrates three common encoding methods: value replacement, label encoding, and one-hot encoding, applied to a single column of a dataset. However, these approaches can be extended to multiple columns as needed.

## Setup

### Prerequisites

* Python
* pandas
* numpy

### Installing

You can install the required libraries using the following commands:

```
pip install pandas
pip install numpy
```

## Running the Tests

### Part 1: Replacing Values

In this exercise, you'll learn how to replace categorical values with user-defined numerical values using the `replace()` function in pandas. This method allows you to assign specific numbers to categories based on your business requirements.

### Part 2: Label Encoding

This exercise introduces label encoding, a technique that converts each category in a column to a numerical label between 0 and n_categories-1. You'll use the `cat.codes` method to perform this encoding.

### Part 3: One-Hot Encoding

In this part, you'll create a new binary column for each unique category using the `get_dummies()` function in pandas. This method is commonly used for machine learning models that require categorical features to be represented as numerical values.

## Usage

1. Clone or download this repository.
2. Open the Jupyter Notebook file or Python script corresponding to the lab exercises.
3. Follow the instructions within the code to complete each part of the lab.

## Deployment

As this project is primarily designed for educational purposes and code exploration, there is no specific deployment process. The provided code and exercises can be run locally on your machine using Jupyter Notebook or Python scripts.

## Author

Ravneet Singh

## License

This project is provided for educational purposes. Any use of this project beyond educational purposes requires explicit permission, and proper credit must be given to the original source.

## Acknowledgements

This lab is a part of the data analytics curriculum provided by Durham College. Special thanks to the instructors and course developers for their efforts in creating this educational resource.
