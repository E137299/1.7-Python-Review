# 1.7-Python-Review: 2D Lists

## Python Review Notes
[Notes](https://drive.google.com/drive/folders/1qjB9FMWxZHhXOouDr0D22zN7S0-rF4_w?usp=drive_link)

## Creating a Diagonally Patterned Two-Dimensional Array
**Objective:**  Write a Python script to create a two-dimensional array of size \( n \times n \) following specific rules and print the resulting array.

### Instructions:
**Input Collection**
- The program will receive a single integer n, representing the size of the array (both rows and columns).

**Array Construction**
- Populate the array according to the following rules:
  - Place `0` on the main diagonal (where the row index equals the column index).
  - Place `1` on the diagonals immediately adjacent to the main diagonal.
  - Place `2` on the next diagonals adjacent to those with `1`, and so on.

**Output**
- Print the resulting n×n array.

**Example**
- For \( n = 4 \), the output should be:
    ```
    0 1 2 3
    1 0 1 2
    2 1 0 1
    3 2 1 0
    ```

- For \( n = 3 \), the output should be:
    ```
    0 1 2
    1 0 1
    2 1 0
    ```
<br></br><br></br>
## Halve a Two-Dimensional Array
**Objective:**  Write a Python script to create a two-dimensional array of size \( n \times n \) following specific rules and print the resulting array.

### Instructions: 
**Input Collection**
- The program will receive a single integer \( n \), representing the size of the array (both rows and columns).

**Array Construction**
- Populate the array according to the following rules:
  - Place `1` on the antidiagonal (the diagonal from the top-right to the bottom-left, where the sum of the row and column indices equals \( n-1 \)).
  - Place `0` on the diagonals above the antidiagonal.
  - Place `2` on the diagonals below the antidiagonal.

**Output**
- Print the resulting \( n \times n \) array.

**Example**
- For \( n = 4 \), the output should be:
    ```
    0 0 0 1
    0 0 1 2
    0 1 2 2
    1 2 2 2
    ```

- For \( n = 3 \), the output should be:
    ```
    0 0 1
    0 1 2
    1 2 2
    ```

<br></br><br></br>
## Swapping Columns in a Two-Dimensional List
**Objective:**  Write a Python script to swap two specified columns in a m x n two-dimensional list and print the resulting list.

### Instructions:
**Input Collection**
- The program will receive two integers: \( m \) (number of rows) and \( n \) (number of columns).
- Then, the program will receive \( m \) rows of \( n \) integers, representing the two-dimensional list.
- Finally, the program will receive two non-negative integers \( i \) and \( j \), both less than \( n \), indicating the columns to be swapped.

**Column Swapping**
- Swap the elements of column \( i \) with the elements of column \( j \) in the two-dimensional list.

**Output**
- Print the resulting two-dimensional list after the columns have been swapped.

**Example**
- For input:
    ```
    3 4
    1 2 3 4
    5 6 7 8
    9 10 11 12
    0 2
    ```
    The output should be:
    ```
    3 2 1 4
    7 6 5 8
    11 10 9 12
    ```

- For input:
    ```
    2 3
    4 5 6
    7 8 9
    1 2
    ```
    The output should be:
    ```
    4 6 5
    7 9 8
    ```
<br></br><br></br>
## Creating a Chequered Pattern in a Two-Dimensional Array
**Objective:**  Write a Python script to create a two-dimensional array of size n * m  and populate it with the characters `.` and `*` in a chequered pattern. The top-left corner of the array should contain the character `.`.

### Instructions:
**Input Collection**
- The program will receive two positive integers: n (number of rows) and  m (number of columns).

**Array Construction**
- Create a two-dimensional array of size \( n \times m \).
- Populate the array with the characters `.` and `*` in a chequered pattern such that:
  - The top-left corner (first row, first column) contains the character `.`.
  - Adjacent cells horizontally and vertically should alternate between `.` and `*`.

**Output**
- Print the resulting n * m array.

**Example**

- For \( n = 3 \) and \( m = 4 \), the output should be:
    ```
    . * . *
    * . * .
    . * . *
    ```

- For \( n = 2 \) and \( m = 5 \), the output should be:
    ```
    . * . * .
    * . * . *
    ```

