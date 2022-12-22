Hi, this is just the beginning so we are going to find the keywords. 
```
# Python code to demonstrate working of iskeyword()
 
# importing "keyword" for keyword operations
import keyword
 
# printing all keywords at once using "kwlist()"
print("The list of keywords is : ")
print(keyword.kwlist)
```

Reference Links: [geeksforgeeks](https://www.geeksforgeeks.org/python-keywords/)

### Keywords

#### None 
```
print(False == 0)
print(True == 1)

print(True + True + True)
print(True + False + False)

print(None == 0)
print(None == [])
```
None: This is a special constant used to denote a null value or a void. It’s important to remember, 0, any empty container(e.g empty list) does not compute to None. 
It is an object of its datatype – NoneType. It is not possible to create multiple None objects and can assign them to variables.             
Output:      
```
True
True
3
1
False
False
```
- not: This logical operator inverts the truth value. The truth table for “not” is depicted below. 
- in: This keyword is used to check if a container contains a value. This keyword is also used to loop through the container.
- is: This keyword is used to test object identity, i.e to check if both the objects take the same memory location or not. 
```
# showing logical operation
# or (returns True)
print(True or False)

# showing logical operation
# and (returns False)
print(False and True)

# showing logical operation
# not (returns False)
print(not True)

# using "in" to check
if 's' in 'geeksforgeeks':
	print("s is part of geeksforgeeks")
else:
	print("s is not part of geeksforgeeks")

# using "in" to loop through
for i in 'geeksforgeeks':
	print(i, end=" ")

print("\r")

# using is to check object identity
# string is immutable( cannot be changed once allocated)
# hence occupy same memory location
print(' ' is ' ')

# using is to check object identity
# dictionary is mutable( can be changed once allocated)
# hence occupy different memory location
print({} is {})
```
Output:
```
True
False
False
s is part of geeksforgeeks
g e e k s f o r g e e k s 
True
False
```
