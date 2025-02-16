# Sparse Matrix Operations

This script performs basic operations (addition, subtraction, multiplication) on sparse matrices represented in text files.

## Description

The script reads sparse matrices from text files, where each line represents a non-zero element in the matrix with its row, column, and value. The script can then add, subtract, or multiply two sparse matrices and save the results to an output file.

## Prerequisites

- Python 3.x
- Ensure you have your matrix files in the same directory as the script, and each file should be formatted with lines containing three integers (row, column, value).

## Usage

1. Place your sparse matrix files in the same directory as the script.
2. Each matrix file should contain lines with three integers representing the row index, column index, and value of non-zero elements.
Example of matrix1.txt:Here's a quick example of how to use the script:

Create two matrix files, matrix1.txt and matrix2.txt:
matrix1.txt: 
0 0 5
0 1 8
1 0 3
matrix2.txt: 
0 0 2
1 1 6
Run the script:  python sparse_matrix_operations.py   


                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        
