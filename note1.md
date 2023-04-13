# Data Structures
### Matrices  
- Matrices are a represenation of numbers, symbols, and expressionsin a 2-dimensional array 
- Matrices are created in python by putting a list in a list 

In python, there is no specific data structure that represents a matrix and so when creating you must follow the rules of a matrix
- The rows and columns must have the same number of values 
- All items in the 2d list must have the same data types 

Example: 
```
python
matrix_1 = [
    [5, 2, 1, 3],
    [2, 1, 6, 3]
]
```
### List Comprehension
- List comprehension is a method of creating lists differently than how we've learned before 
Examples of list comprehension:
- Creating a list with exisiting lists
- Creating a list by by applying operations to all of it's items 
- Creating a list with existing lists that satisfies a certain condition 

List Comprenhension must consist of the following 
- A square bracket that contains an expression which describes the list 
- A for clause to explains it's members
- Optional if clauses depending on how complex the list is

Example:
fruits = ["apple", "banana", "cherry", "kiwi", "mango"]

newlist = [x for x in fruits if "a" in x]

print(newlist)

### Map Filter 
