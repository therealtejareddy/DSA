Print numbers from 1 to N without the help of loops.
```
Input:
N = 10
Output: 1 2 3 4 5 6 7 8 9 10
```
```python
def printNos(N):
        if N==0:
            return
        self.printNos(N-1)
        print(N,end=" ")
```
---
Given and integer N.Calculate the sum of series 13 + 23 + 33 + 43 + … till N-th term.
```
Input:
N=5
Output:
225
Explanation:
13+23+33+43+53=225
```
```python
def sumOfSeries(N):
    if N==0:
        return 0
    else:
        return sumOfSeries(N-1)+(N*N*N)
```
---
