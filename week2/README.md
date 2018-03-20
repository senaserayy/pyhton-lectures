# HOMEWORK - WEEK2
### • hw1.py:
```python
import random 

	arr = [None] * 100
	for i in range (1,100):
	    arr[i] = i
	
	arr[0] = random.randint(1,99)
	random.shuffle(arr)
	print (arr)
	
	x = 4950 #1+2+.....+99 = 4950
	total = 0
	for i in range (len(arr)):
	    total += arr[i]
	print ("Duplicate Num: ", total - x)
```
### • hw2.py:
```python
	while True:
	    num1 = input("Num 1: ")
	    num1 = int(num1) - 1
	    num2 = input("Num 2: ")
	    num2 = int(num2)
	    str = input("String: ")
	    str2 = str[num2:]
	    str = str[:num1]
	    print (str,str2)
```
		
### • hw3.py:
```python
	while True:
	    num1 = input("Num 1: ")
	    num1 = int(num1) - 1
	    num2 = input("Num 2: ")
	    num2 = int(num2)
	    str = input("String: ")
	    str2 = str[num2:]
	    str = str[:num1]
	    print (str,str2)
```
		
### • hw4.py:
```python
	while True:
	    str = input(": ")
	    if str == str[::-1]:
		    print ("Polindrome")
	    else:
		    print ("Not Polindrome")
```