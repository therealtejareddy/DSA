```
Input: 5

Output:
1 2 3 4 5
1 2 3 4
1 2 3 
1 2  
1
```
```python
def printTriangle(N):
        for i in range(N):
            for j in range(N-i):
                print(str(j+1)+" ",end="")
            print()
```
---
```
Input: 5

Output:

    *
   ***  
  *****
 *******
*********
```
```python
def printTriangle(N):
    for i in range(N):
        for j in range(N-i-1):
            print(" ",end="")
        for j in range(i+1):
            print("*",end="")
        for j in range(i):
            print("*",end="")
        print()
```
---
```
Input: 5

Output:

*********
 *******
  *****
   ***
    *

*********
```
```python
def printTriangle(N):
    for i in range(N):
        for j in range(i):
            print(" ",end="")
        for j in range(N-i):
            print("*",end="")
        for j in range(N-i-1):
            print("*",end="")
        print()
```
---