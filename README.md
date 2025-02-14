# Tuples in Python 🐍

A **tuple** is an immutable, ordered collection in Python that allows you to store multiple items in a single variable. Unlike lists, tuples cannot be changed after creation, making them useful for fixed data storage.

## 📌 Features of Tuples:
- Ordered and indexed
- Immutable (cannot be modified after creation)
- Can store duplicate values
- Can contain different data types

## 📚 Table of Contents
- [Creating a Tuple](#creating-a-tuple)
- [Accessing Tuple Elements](#accessing-tuple-elements)
- [Tuple Operations](#tuple-operations)
- [Tuple Methods](#tuple-methods)
- [Advantages of Tuples](#advantages-of-tuples)
- [Examples](#examples)

## 🚀 Getting Started
### Creating a Tuple
```python
# Creating a tuple
my_tuple = (1, 2, 3, "Hello", True)
print(my_tuple)
```

### Accessing Tuple Elements
```python
# Indexing
print(my_tuple[0])  # Output: 1

# Slicing
print(my_tuple[1:4])  # Output: (2, 3, 'Hello')
```

### Tuple Operations
```python
# Concatenation
tuple1 = (1, 2, 3)
tuple2 = (4, 5, 6)
combined = tuple1 + tuple2
print(combined)  # Output: (1, 2, 3, 4, 5, 6)

# Repetition
print(tuple1 * 2)  # Output: (1, 2, 3, 1, 2, 3)
```

### Tuple Methods
```python
my_tuple = (1, 2, 3, 4, 2, 2)
print(my_tuple.count(2))  # Output: 3
print(my_tuple.index(3))  # Output: 2
```

### Advantages of Tuples
✔ Faster than lists (performance boost in large datasets)
✔ Useful for read-only collections
✔ Can be used as dictionary keys

## 🎯 Example Use Cases
- Storing coordinate points (x, y, z)
- Defining fixed configuration settings
- Using as keys in dictionaries

## 🛠 Contributing
Feel free to contribute! Fork the repo, create a feature branch, and submit a PR. 😊

## 📜 License
This project is open-source and available under the [MIT License](LICENSE).
