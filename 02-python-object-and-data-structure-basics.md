# 2. Python Object and Data Structure Basics

## Python Data Types
| Name | Data type | Description |
| ----------- | ----------- | ----------- |
| Integers | int | Whole numbers, such as 300 |
| Floating point | float | Numbers with a decimal point, such as 2.3 |
| Strings | str | Ordered sequence of characters, such as "Hello", '20' |
| Lists | list | Ordered sequence of objects: [10, "Hi", 2.3] |
| Dictionaries | dict | Unordered key:value pairs: {"key1":"val1", "key2":"value2"} |
| Tuples | tup | Ordered immutable sequence of objects: (10, "hi", 2.3) |
| Sets | set | Unordered collection of unique objects: {"a", "b"} |
| Booleans | bool | Logical value indicating True or False |

### Python numbers
Basic arithmetics see the notebook. 

### Variable Assignments
It is considered best practice that `names are lower case`, except for global variables. 

Python uses `Dynamic Typing`, which means you can reassign variables to different data types. It makes Python flexible in assigning data types, different than other languages that are Statically-Typed. Something like this is okay in Python:
```python
my_dogs = 2
my_dogs = ["Sammy", "Frankie"]
```

Pros of Dynamic Typing: Easy to work with; Faster development time.

Const of Dynamic Typing: May result in bugs for unexpected data types; You need to be aware of `type()`. 

### Strings
Strings are ordered sequences of characters using the syntax of dingle quotes or double quotes. The nice thing about having two choices is that if you have one type of quote in your string that you want to keep, you can use the other type of quote to wrap it, such as `"I don't know. "`. 

Python also use reverse indexing: 
```
Character:     h  e  l  l  o
Index:         0  1  2  3  4
Reverse Index: 0 -1 -3 -2 -1
```

### Indexing and Slicing with Strings
See notebook. 

### String Properties and Methods
See notebook. 

### Print formatting with strings
See notebook. 

### Lists in Python
Lists are ordered sequences that can hold a variety of object types. They use [] brackets and commas to separate objects in the list. [1, 2, 3, 4, 5]. Lists support indexing and slicing. Lists can be nested an also have a variety of useful methods than can be called off of them. 

See notebook. 

### Dictionaries in Python
Dictionaries are unordered mappings (key-value pairs). They cannot be sorted. 

### Tuples
Tuples are very similar to lists, but tuples are immutable. Once an element is assigned to a index position inside a tuple, it cannot be reassigned. 

When you pass objects in code, to make sure it doesn't get accidentally changes, use tuples. 

### Sets in Python
Unordered collections of unique elements. 

### Booleans


### I/O with basic files in Python









