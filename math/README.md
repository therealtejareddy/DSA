Given a 32 bit number X, reverse its binary form and print the answer in decimal.
```
Input:
X = 1
Output:
2147483648 
Explanation:
Binary of 1 in 32 bits representation-
00000000000000000000000000000001
Reversing the binary form we get, 
10000000000000000000000000000000,
whose decimal value is 2147483648.
```
```python
def reversedBits(X):
        X = bin(X)[2:]
        X = (32-len(X))*'0'+X
        X = X[::-1]
        X = int(X,2)
        return X
```
***
Given an integer, check whether it is a palindrome or not.
```
Input: n = 55555
Output: Yes
```
```python
def is_palindrome(self, n):
    if str(n)==str(n)[::-1]:
        return 'Yes'
    else:
        return 'No'
```