# Understanding variables

## Declaring variables

### Single variables
You provide the `variable name` and assign it a `value` using `=` sign

*Syntax*
```python
<variable name> = <value>
```

*Example*
```python
myName = Duncan
```

### Multiple variables
- same type
```python
a, b, c, = 2, 4, 6
```

- different types
```python
name, age = "Maya", 24
```

***NOTE:*** - Types are evaluated at run time and not during compile time

### Value increments
*Correct syntax*
```python
n = n + 1
# or
n += 1
```

*Not supported*
The following is not valid syntax in Python
```python
n++
```

Python has a `NULL` type but it's called `None` instead