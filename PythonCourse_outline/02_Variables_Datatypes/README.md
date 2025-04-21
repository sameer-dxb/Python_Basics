2. **Variables & Data Types** – Variable assignment,Strings, Integers, Floats, Booleans, Lists, Dictionaries

This section covers the basics of Python variables and data types.

### Files:
- `variables_example.py` – Simple intro to variables
- `strings_demo.py` – String usage, methods, formatting
- `numbers_demo.py` – Integers, floats, math operations
- `booleans_demo.py` – Boolean logic and true/false examples



# ✅ Python Data Types to Learn

## 1. Numeric Types (int, float, and complex)

### int
a = 10
print("Integer:", a, type(a))

### float
b = 3.14
print("Float:", b, type(b))

### complex
c = 2 + 3j
print("Complex:", c, type(c))


## 2. Boolean Type  ## bool – Represents True or False
x = True
y = False

print(x, type(x))
print(y, type(y))

## 3. Text Type str – For textual data

name = "Sameer"

print(name, type(name))

## 4. Sequence Types  (list, tuple, range)
### list
my_list = [1, 2, 3]
print(my_list, type(my_list))

### tuple
my_tuple = (1, 2, 3)
print(my_tuple, type(my_tuple))

### range
my_range = range(5)
print(list(my_range), type(my_range))


## 5. Set Types  (set, frozenset)
### set
my_set = {1, 2, 2, 3}
print(my_set, type(my_set))  # duplicates removed

### frozenset
frozen = frozenset([1, 2, 3])
print(frozen, type(frozen))
