# Python Basics part 2
## Scripts
Last week we used the REPL to write interactive Python programs.
Typically you will not do this. Typically you will write all of your commands into a file or a bunch of files, and then run the files.

Start by trying to write loops in the repl and see how frustrating it is. Python is white space sensitive! Introduce scripts.

## Loops
### for loops
* loop by range
* loop over container
  
### while loops
* loop so long as a condition is true
  
## Conditionals
* if/else
* if/elif/else



## Functions
### Functions that give us values
Sometimes you want to do a bunch of things, but bundle all of things you are doing into a logic chunk. This is what functions are for. They are reusable and modular.

### Functions that don't return values
Last week we saw one of these. print(). print() doesnt give us anything, it just does something. 
Another function that does this is list.append()


## Remember! Python is White Space Sensitive!
Look back at loops and conditionals and remember - Python is white space sensitive! Tabs and 4 spaces might *look* the same on your computer, but they are not the same.
Computers use bytes to represent data.
A tab is a byte, a space is a different byte. Even though you might look at a tab and 4 spaces and see the same thing, Python knows the difference and will complain about it.
