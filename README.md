AIM : STUDY OF LIST

THEORY : 
A list in Python is a collection data type used to store multiple items in a single variable. Lists are ordered, mutable, and can contain duplicate values as well as different data types.

1. Creating a List-
A list is created by placing elements inside square brackets.

listfruits = ["apple", "orange", "cherry"]


2. Accessing Elements-
Single elements can be accessed using indexing.
Negative indexing accesses elements from the end.

listfruits[0]
listfruits[-2]


3. Printing Elements-
Entire list or specific elements can be printed using print().


4. Adding Elements-
append() is used to add an element at the end of the list.
insert() is used to add an element at a specific position.

listfruits.append("banana")
listfruits.insert(1, "banana")


5. Replacing Elements-
Elements can be replaced by assigning a new value to an index.

listfruits[1] = "banana"


6. Repeating Elements-
Lists allow duplicate values.

["apple", "orange", "apple", "cherry"]


7. Length of List-
len() function returns the number of elements in a list.

len(list1)


8. Combining Lists-
Lists can be combined using + operator.
extend() adds elements of one list to another.

list1 + list2
list1.extend(list2)


9. Slicing of List-
Slicing is used to access a range of elements.

list1[2:5]
list1[1:]
list1[:4]

CONCLUSION :
From this experiment, it is concluded that lists in Python are a flexible and powerful data structure used to store and manage multiple values efficiently. Lists allow easy insertion, deletion, replacement, slicing, and combination of elements. They support indexing and negative indexing, can store heterogeneous data, and allow duplicate elements. Hence, lists are widely used in Python programming for handling grouped data in a simple and effective manner.
