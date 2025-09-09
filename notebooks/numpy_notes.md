# NumPy Basics 


What is NumPy?

NumPy is like a super calculator for Python.

It helps us work with numbers in arrays (a box with rows and columns, like a school timetable).

It is faster than normal Python lists when we do big math.

🟢 What is an Array?

Think of an array as a list of numbers in a box.

Example:

1D array (a row): [1, 2, 3, 4]

2D array (a table):

[[1, 2, 3],
 [4, 5, 6]]

🟢 Creating Arrays
import numpy as np

# 1D array
arr1 = np.array([1, 2, 3, 4])
print("1D array:", arr1)

# 2D array
arr2 = np.array([[1, 2, 3], [4, 5, 6]])
print("2D array:\n", arr2)

🟢 Slicing (Cutting Arrays)

Like cutting a cake 🍰 into pieces.

arr = np.array([10, 20, 30, 40, 50])

print(arr[0])   # First element → 10
print(arr[1:4]) # From 2nd to 4th → [20 30 40]
print(arr[-1])  # Last element → 50

🟢 Array Operations (Math on Arrays)

We can add, subtract, multiply arrays easily (like magic ).

a = np.array([1, 2, 3])
b = np.array([4, 5, 6])

print(a + b)   # [5 7 9]
print(a * b)   # [4 10 18]
print(a ** 2)  # [1 4 9]

🟢 Useful Functions
arr = np.array([1, 2, 3, 4, 5])

print("Sum:", arr.sum())         # 15
print("Mean (average):", arr.mean()) # 3.0
print("Max:", arr.max())         # 5
print("Min:", arr.min())         # 1

✅ Notes

Arrays are faster and easier for big math problems.

1D array = row, 2D array = table.

Slicing = take a part of array.

Operations = add, multiply, square, etc., works element-wise.

Useful functions help summarize arrays quickly (sum(), mean(), max(), min()).
