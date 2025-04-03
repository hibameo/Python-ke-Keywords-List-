# Python Keywords List

Python ke **keywords** wo reserved words hain jo Python programming language me special meaning rakhte hain. Ye identifiers ya variable names ke tor par use nahi ho sakte. Yeh built-in functionality provide karte hain.

## 🔹 Python ke Keywords (Python 3.10 ke mutabiq)

### ✅ **Control Flow Keywords**
- `if` 
- `elif` 
- `else` 
- `for` 
- `while` 
- `break` 
- `continue` 
- `pass`

### ✅ **Boolean & None Keywords**
- `True` 
- `False` 
- `None`

### ✅ **Logical Operators**
- `and` 
- `or` 
- `not`

### ✅ **Function & Class Related Keywords**
- `def` 
- `return` 
- `yield` 
- `lambda`
- `class`

### ✅ **Exception Handling Keywords**
- `try` 
- `except` 
- `finally` 
- `raise`
- `assert`

### ✅ **Import Related Keywords**
- `import` 
- `from` 
- `as`

### ✅ **Scope & Variable Related Keywords**
- `global` 
- `nonlocal`

### ✅ **Miscellaneous Keywords**
- `del` 
- `with` 
- `is` 
- `in`

## 🔹 **Example Usage**

```python
# if-else example
x = 10
if x > 5:
    print("x is greater than 5")
else:
    print("x is 5 or less")

# for loop example
for i in range(5):
    print(i)

# function example
def greet(name):
    return f"Hello, {name}!"

print(greet("Hiba"))

# try-except example
try:
    num = int("abc")  # Error aayega
except ValueError:
    print("Invalid number!")
```

