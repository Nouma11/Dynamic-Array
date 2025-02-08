# Dynamic Array Implementation in C++

## Overview
This project provides a **custom implementation of a dynamic array** in C++ without using built-in STL containers like `vector`. It supports **resizing, inserting, deleting, reversing, searching, and clearing** elements dynamically.

## Features
- ✅ **Dynamic Memory Allocation**: Allows resizing the array dynamically.
- ✅ **Insertion Methods**:
  - Insert at the beginning.
  - Insert at a specific index.
  - Insert at the end.
- ✅ **Deletion Methods**:
  - Delete a specific item by index or value.
  - Delete the first or last item.
- ✅ **Utility Functions**:
  - Get item by index.
  - Reverse the array.
  - Find an item by value.
  - Check if the array is empty.
  - Print the array.

## Functions

### **Core Functions**
| Function | Description |
|----------|-------------|
| `SetItem(index, value)` | Sets an item at a given index. |
| `GetItem(index)` | Retrieves an item at a specific index. |
| `Size()` | Returns the size of the array. |
| `IsEmpty()` | Checks if the array is empty. |
| `PrintList()` | Prints the elements of the array. |

### **Insertion Functions**
| Function | Description |
|----------|-------------|
| `InsertAt(index, value)` | Inserts an item at a specific index. |
| `InsertAtBeginning(value)` | Inserts an item at the beginning of the array. |
| `InsertAtEnd(value)` | Inserts an item at the end of the array. |
| `InsertBefore(index, value)` | Inserts an item before a specific index. |
| `InsertAfter(index, value)` | Inserts an item after a specific index. |

### **Deletion Functions**
| Function | Description |
|----------|-------------|
| `DeleteItemAt(index)` | Deletes an item at a given index. |
| `DeleteFirstItem()` | Deletes the first item of the array. |
| `DeleteLastItem()` | Deletes the last item of the array. |
| `DeleteItem(value)` | Deletes the first occurrence of a value. |
| `Clear()` | Clears the entire array. |

### **Utility Functions**
| Function | Description |
|----------|-------------|
| `Resize(newSize)` | Resizes the array to a new size. |
| `Reverse()` | Reverses the array order. |
| `Find(value)` | Returns the index of the first occurrence of a value, or `-1` if not found. |

## Installation & Usage
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/DynamicArray.git
   cd DynamicArray
