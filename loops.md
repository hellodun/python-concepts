# Understanfing Loops

### Looping from 0 to 4
### while loop
```py
n = 0
while n < 5: # block is followed by a collon
    print(n)
    n += 1
```

### for loop
```py
for i in range(5):
    print(i)
```

- With for loops, `i` is incremented by default/implicitely


***Looping from 2 to 7***
```py
for i in range(2, 8):
    print(i)
    # increases from the indicated number up to n-1, where n is the last value in range
```

***Looping in descending order***
***Looping from 10 to 4***
```py
for i in range(10, 3, -1):
    print(i)
    # decreases from the indicated number up to n+1, where n is the last value in range, and -1 is the value indication we're decreasing
```