
# Mean-Variance-Standard Deviation Calculator

## Project Overview

This project is part of the freeCodeCamp Data Analysis with Python certification.

It uses Python and NumPy to calculate statistical measurements from a list of nine numbers arranged in a 3 × 3 matrix.

## Features

The calculator performs six statistical calculations:

1. Mean
2. Variance
3. Standard Deviation
4. Maximum
5. Minimum
6. Sum

Each calculation provides results for:
- Columns
- Rows
- The entire matrix

## Technologies Used

- Python
- NumPy

## How It Works

The calculate() function accepts a list containing exactly nine numbers and converts it into a 3 × 3 NumPy array.

It then performs the required statistical calculations and returns the results in a dictionary.

If the input contains fewer or more than nine numbers, a ValueError is raised.

## Example

Input:

[0, 1, 2, 3, 4, 5, 6, 7, 8]

Output:

A dictionary containing the mean, variance, standard deviation, maximum, minimum and sum.

## Author

Themba Polile

Lesotho
