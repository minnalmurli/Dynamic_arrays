# Dynamic_arrays

# `list_of_me`: A Dynamic Array Implementation in Python

`list_of_me` is a Python class that provides a dynamic array similar to Python's built-in list. It is implemented using a C-style array, offering basic functionality such as appending, deleting, finding, and inserting elements.

## Features

- **Dynamic Resizing**: Automatically adjusts the array's capacity when elements are added or removed.
- **Basic List Operations**:
  - `append(item)`: Adds an item to the end of the list.
  - `pop()`: Removes and returns the last item.
  - `remove(item)`: Removes the first occurrence of the specified item.
  - `insert(pos, item)`: Inserts an item at the specified position.
  - `clear()`: Clears all elements from the list.
- **Indexing and Length**:
  - `__getitem__(index)`: Accesses an element by its index.
  - `__len__()`: Returns the number of elements in the list.
- **Utility Functions**:
  - `find(item)`: Finds the index of the first occurrence of the item.
  - `__str__()`: Returns a string representation of the list.

## Methods and Usage

### 1. **Initialization**
```python
my_list = list_of_me()
