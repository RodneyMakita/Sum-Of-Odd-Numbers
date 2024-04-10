
# Row Sum of Odd Numbers

![Python Version](https://img.shields.io/badge/python-3.6%2B-blue)
![License](https://img.shields.io/badge/license-MIT-green)

This Python module calculates the sum of numbers in the nth row of a triangle of consecutive odd numbers.

## Introduction

Given a triangle of consecutive odd numbers:


                  1
                3   5
              7   9   11
          13    15   17  19
        21  23   25    27   29
        ...



This module provides a function `row_sum_odd_numbers(n)` which calculates the sum of the numbers in the nth row of this triangle.

## Installation

you can copy the `row_sum_odd_numbers.py` file into your project directory.

## Usage

To use the `row_sum_odd_numbers` function, simply import it and provide the row number as an argument:

```python
from row_sum_odd_numbers import row_sum_odd_numbers

# Calculate the sum of numbers in the 5th row
result = row_sum_odd_numbers(5)
print("Sum of numbers in the 5th row:", result)
Examples

from row_sum_odd_numbers import row_sum_odd_numbers

# Example 1: Calculate the sum of numbers in the 1st row
print(row_sum_odd_numbers(1))  # Output: 1

# Example 2: Calculate the sum of numbers in the 2nd row
print(row_sum_odd_numbers(2))  # Output: 8

```
### Contributing
Contributions are welcome! If you have any suggestions, improvements, or feature requests, feel free to open an issue or create a pull request.

### License
This project is licensed under the MIT License - see the LICENSE file for details.






