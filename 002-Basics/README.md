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
lists
tuples
sets
dictionaries
use type() to show the types of things

## Loops
for 
while

## Conditionals
if

## Remember! Python is White Space Sensitive!
Look back at loops and conditionals and remember - Python is white space sensitive! Tabs and 4 spaces might *look* the same on your computer, but they are not the same.
Computers use bytes to represent data.
A tab is a byte, a space is a different byte. Even though you might look at a tab and 4 spaces and see the same thing, Python knows the difference and will complain about it.
