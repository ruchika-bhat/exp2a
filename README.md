AIM : STUDY OF LIST

ALGORITHM :

* Algorithm for 1st question -
1.Start
2.Create a list of 5 student names
3.Display first and last student name
4.Add a new student to the list
5.Remove one student from the list
6.Sort the list alphabetically
7.Display the final list
8.Stop

* Algorithm for 2nd question -
1.Start
2.Create a list of student marks
3.Display highest and lowest marks
4.Calculate and display average marks
5.Sort the marks in ascending order
6.Display the sorted list
7.Stop


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
