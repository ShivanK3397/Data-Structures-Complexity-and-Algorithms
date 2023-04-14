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
```
python
fruits = ["apple", "banana", "cherry", "kiwi", "mango"]

newlist = [x for x in fruits if "a" in x]

print(newlist) 

```
### Map Function
- The map function is a function that allows you to apply a function to iterable data 
- The formattting of this function is like so map(function_name, sequence of iterable data)
- The map function returns an python iterable type of data 
- This allows you to create list's with this function 

Example: 
```
python
```
### Filter Function 
- The filter function works by filtering data from an sequence of iterable data that meets a certain condition 
- The formatting of the function is like so filter(function_name, sequence of iterable data)
- The function that you use must return a boolean value so that the filter function can check to see if the condition is met. Doing otherwise will result in an error in your code

### Tuples 
- Tuples are a type of data structure in python 
- Tuples offer the following features, immutability, allows different datatypes as items, is iterable, is slicable and indexable, and is nestable
- Tuples are created with paranthesis, the round brackets Ex: ()

#### Tuple Operators 
- Tuple, like strings and list's have operators that can be used on them 
- Concentaion, which adds the two tuples together, repetion which repeats the tuple multiple times, and membership, which checks if a value is in a tuple are all operators that tuples have
- These operators work similary to how the operators work on 

#### Indexing and Slicing 
- Tuples can be indexed and sliced the same way that lists are, with square brackets []
Example:
```
python
tup = (1,4,65,4)

print(tup[2])
print(tup[::-1])
```
Output:
65
(4,64,4,1)

#### Built-In Functions 
Tuples, like all other data structures in python have a lot of built in functions. 
Example of Built-In Functions:
- len() finds the length of the tuple
- min() finds the smallest value in the tuple
- max() finds the largest value in the tuple 

#### Tuple Comprehension
-  Tuples comprehension works similarly to list comprehension
- As their both iterable data types, tuple comprehension follows the same general format as list comprehension

#### Tuple Packing and Unpacking 
- Tuples can be both packed ane unpacked
- Packing in coding terms simply means packing togther multiple variables into a tuple with unpacking being the opposite 
```
python
var1 = 'hello'
var2 = 'world'
var3 = 63
var4 = 'print'


tup = var1, var2, var3, var4

print(tup)
```
Output: 
('hello','world',63,'print')

### Sets

### Dictionary  .........................................................................................
