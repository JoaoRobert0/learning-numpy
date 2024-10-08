# Learning NumPy

This repository is dedicated to simple exercises for practicing the fundamental capabilities of NumPy, a powerful library for numerical computing in Python. Each exercise is designed to help you get familiar with different features and functionalities of NumPy.

## Exercises

1. **Array Creation**
   - Create an array of zeros with size 5.
   - Create an array of integers from 10 to 20.
   - Create an array of random integers between 0 and 100 with size (3, 3).

2. **Indexing and Slicing**
   - Given the array `arr = np.array([1, 2, 3, 4, 5])`, access the third element.
   - Create a 2D array of shape (4, 4) and access the entire second row.
   - Given an array `arr = np.arange(25).reshape(5, 5)`, extract the subarray containing the first two rows and the first three columns.

3. **Mathematical Operations**
   - Create two arrays of size 5 and perform element-wise addition and multiplication between them.
   - Multiply all elements of an array by 10.
   - Create an array of integers and calculate the mean, sum, and maximum value.

4. **Reshaping**
   - Create an array of numbers from 1 to 16 and reshape it into a 4x4 array.
   - Transpose the previous array (swap rows and columns).
   - From a 3D array with shape (2, 3, 3), flatten it into a 2D array.

5. **Broadcasting**
   - Create a (3, 3) size integer array and add 10 to each element of the array without using loops.
   - Multiply a 1D array of size 3 by a 2D array of size (3, 3).

6. **Masks and Conditions**
   - Create a random integer array of size (5, 5) and use a mask to replace all values less than 10 with 0.
   - Given the array `arr = np.array([10, 5, 8, 12, 6, 2])`, create a mask to select only the values greater than 6.

7. **Concatenation and Division**
   - Create two arrays of shape (2, 3). Concatenate them along axis 0 (rows) and axis 1 (columns).
   - Divide an array of 10 elements into 2 arrays of equal size.

8. **NumPy Specific Functions**
   - Create an array of integers from 0 to 9 and calculate the sine of each number.
   - Create an array of values from 1 to 100 and find the indices of the values that are divisible by 5.

## Installation

To use NumPy, you need to have Python installed on your machine. You can install NumPy using pip:

```bash
pip install numpy
