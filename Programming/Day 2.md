---
tags:
  - python
  - list
  - string
  - split
Author: Diksha Bhati
date: 2025-06-16
Start Time: 
End Time: 
Status: In-Progress
---
> [!Problem Statement]
> 
> 
> 
> 
### Clear Day 
Chef classifies a day to be either `rainy`, `cloudy`, or `clear`.

In a particular **week**, Chef finds XX days to be `rainy` and YY days to be `cloudy`.  
Find the number of `clear` days in the week.

### Input Format

- The first and only line of input will contain two space-separated integers XX and YY, denoting the number of rainy and cloudy days in the week.

### Output Format

Output the number of clear days in the week.

[Link ](https://www.codechef.com/practice/course/basic-programming-concepts/DIFF500/problems/CLEARDAY)


```python
_input = input()

var1 = _input.split(" ")

x = int(var1[0])
y = int(var1[1])

print(7-x-y)

```


Or 

```python
var1 = input().split(" ")

x = int(var1[0])
y = int(var1[1])

print(7-x-y)

```

or 

```python
x, y  = input().split(" ")

print(7-int(x)-int(y))
```

or 

```python

print(7 - sum([int(item) for item in input.split(" ")]))

```


```python
x = "things will become tough now"
print(x) #things will become tough now
print(type(x)) #  <class 'str'> --> Data type 

y = x.split(" ")
print(y) # ['things', 'will', 'become', 'tough', 'now']
print(y[2]) #become

print(y[17])
"""
Traceback (most recent call last):
  File "<python-input-46>", line 1, in <module>
    print(y[17])
          ~^^^^
IndexError: list index out of range
 %%
"""
print(y[4]) # now
```



To Read 

[String Split](https://www.w3schools.com/python/ref_string_split.asp)
[List Python](https://www.w3schools.com/python/python_lists.asp)
