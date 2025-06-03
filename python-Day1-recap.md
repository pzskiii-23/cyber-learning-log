# Python Day 1 – Loops and Functions

## What I learned
- How to use `for` loops to repeat code for each item in a list.
- How to use `while` loops to repeat code while a condition is true.
- How to define and call my own functions with `def`.
- How to use the `.upper()` method to print text in uppercase.

## Code examples

""" Exercise code
 For - repeating something x times
for i in range(5):
    print("This is number", i)

 Practical example - checking the port list
ports = [22, 80, 443]
for port in ports:
    print("Checking port", port)

 While – repeat while something is true
count = 0
while count < 5:
    print("Count to:", count)
    count += 1

 def function - we pack the code into a "box"
def greeting(name):
    print("Hello", name, "nice to meet you")
greeting("Adrian")
"""

# Task done independently
words = ["cybersecurity", "is", "awesome"]
for word in words:
    print(word.upper())

## Summary

What was easy:  
Creating lists, using for loops, and calling simple functions.

What was tricky:  
Understanding the difference between for and while loops, but it's clear now.

What I learned:  
How to use basic loops and functions in Python, how to process a list, and how to manipulate text with string methods.  
I'm ready to move on to writing my own functions with user input and more practical scripts for cyber tasks.
