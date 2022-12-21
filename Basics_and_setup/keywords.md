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
