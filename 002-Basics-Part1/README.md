# Python Basics Part 1

## Data types
* string - text
* int - whole numbers
* float - numbers with a decimal point

# Your first functions!

| function | what it does |
| --- | ---|
| `print()` | will print something out |
| `type()` | will tell you the type of something |

Try this!
```
>>> type(5)
# see the output
>>> type(4.3)
# see the output
>>>type("hello")
# see the output
>>> x = 1
>>> type(x)
# see the output
```

## Operators
| operator | what it does |
| --- | --- |
| `+` | adds |
| `-` | subtracts |
| `*` | multiplies  |
| `/` | divides |

Above I tell you what these operators do for numbers. You can also use + and * with strings
```
>>> "hello" + " " + "world"
#see the output
>>> "hello" * 3
# see the output
```

## A couple more operators
| operator | what it does |
| --- | --- |
| `+=` | adds in place |
| `-=` | subtracts in place |
| `*=` | multiplies  in place |
| `/=` | divides in place |

## Variables
While coding you will save your values in variables to give them meaningful names and to be able to do operations on them.
There are 3 main styles people use for naming variables
| Style | Example |
| --- | --- | 
| snake case  | my_name, favorite_food, month_of_year |
| camel case | likeThis, anAnimal, myFavorite |
| pascal case | LikeThis, AnAnimal, MyFavorite |

Read more [here](https://peps.python.org/pep-0008/)

## Data structures
### List
A container of values.
```
>>> myList = [1, 2, 3]
>>> type(myList)
# output
>>> print(myList)
# see output
>>> print(myList[0])
# see output
>>> print(myList[3])
# error! lists are 0-indexed
```

In Python, lists can contain any data type!
```
>>> stuff = [1, 2.4, "hello", 5, 3.4]
>>> print(stuff)
# output
>>> print(stuff[0])
# output
>>> print(stuff[6])
# error
```

You can add things to lists
```
>>> l = []
>>> l.append(1)
>>> l.append("hi")
>>> print(l)
```
### What can list do?
Take a look at `dir(list)`

### Python containers are zero-indexed.
See also: `insert()`, del

### Other list methods
`pop()`, `remove()`, `clear(), `reverse()` and `sort()`.

### Tuple
Like a list, but **immutable**

```
>>> myTuple = (1, 2, 3)
>>> print(myTuple)
# see output
>>> type(myTuple)
# see output
```

tuples are immutable. Once you create a tuple, you cannot insert or remove new items.

### Sets
A container of values that only contains ONE instance of any value.

### Dictionaries
Like a list, but indexed by keys and not by numeric index.
A very useful datatype.


