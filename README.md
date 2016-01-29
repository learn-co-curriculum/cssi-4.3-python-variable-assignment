
#Python Variable Assignment

#Objectives:

+ Understand common python syntax and datatypes
+ Understand how to assign variables
+ Learn python syntax for variable assignment

#Motivation
Python is a powerful programming language - it's a tool that you will be able to use to solve many different kinds of problems. Just like we can only solve problems with English once we have the basic rules down, we have to know the basics. We'll translate some of the programming concepts we learned in javascript into python, and practice with lots of exercises and labs.

If you get stuck, remember that you're not just learning to program - you're learning to learn. Try searching the official Python documentation and googling for answers. If you can't figure out how to phrase the search, or you searched and can't find results, try to work it out with those around you. If neither of you can figure it out, there are plenty of TAs and instructors - we'll probably find you before you even call us, but don't hesitate.

#Variable Assignment
Variables are like buckets that store pieces of information. We name the variable and fill it with pieces of data that are relevant. Variables can store any type of data (strings, integers, floats, etc).

In python we don't need var or a ; to declare a variable
```
> var x = 15;
> x
15
```
# Variable Re-assignment
Just like in javascript, we can change what's in the box at any time.
```
>>> minion = "Kevin"
>>> print minion
Kevin
```
What will happen when we run the following?
```
>>> name = "Kevin"
>>> name = "Carl"
>>> print name
```

On the first line, we assigned the variable name to store Kevin. On the next line, we reassigned the value of the variable name to store Carl. Each variable can only store one value, so we overwrote name, replacing what was inside with the new value. When we print name on the last line, we will see Carl - the last thing we assigned to name.

#Naming Conventions

 When we name a variable, we use all lowercase letters. Variable names can not have spaces but instead use underscores this_style_is_called_snake_case.

<p data-visibility='hidden'>View <a href='https://learn.co/lessons/cssi-4.3-python-variable-assignment' title='Python Variable Assignment'>Python Variable Assignment</a> on Learn.co and start learning to code for free.</p>
