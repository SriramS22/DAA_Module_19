# EX 1D Linear search
## DATE:
## AIM:
To write a python program for a search function with parameter list name and the value to be searched using string values.



## Algorithm
1. Start by reading the number of elements and the string values into a list.
2. Define a function search(List, n) that takes the list and the value to be searched. 
3. Loop through each element in the list.
4. If the current element matches the value n, return True. 
5. If no match is found after checking all elements, return False   

## Program:
```python
/*
Program to implement a search function with parameter list name and the value to be searched using string values.
Developed by: sriram s
Register Number: 212222240105
*/

def search(List,n):
    for i in range(len(List)):
        if List[i]== n:
            return True
    return False
List = []
x = int(input())
for i in range(x):
    List.append(input())
n = input()    
if search(List,n):
    print("Found")
else:
    print("Not Found")
```

## Output:

![image](https://github.com/user-attachments/assets/dc95232f-f4a0-4427-9b3d-33cfeb6f7c3e)



## Result:
The program was executed successfully, and it correctly checks if the input element is present in the list, printing "Found" if the element exists or "Not Found" if it does not.
