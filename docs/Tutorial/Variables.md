---
layout: default
title: Variables
parent: Tutorial
nav_order: 3
---
# **An Introduction to Variables**

### What is a Variable?

A variable is one of the most important concepts in all of programming. A variable allows us to store data (like numbers, words, or anything else) which we can use in our programs.

### How do we give variables a value?

In Python, variables are assigned (given a value) by using an equals (=) sign. We give our variable a name so we can access and modify the value later on. For example, to create a variable called "welcome" with a value of "Hello!", we would use:\
`welcome = "Hello!"`\
We have to put the Hello! in quotes, just like we have to for print, since it is a *string*, which is the fancy programming name for a word or sentence.\
We can change the value of a variable at any time by using the same format. If we want to change the value of welcome to "Hi!", we would use:\
`welcome = "Hi!"`

### How do we access the value of variables?

We can access the value of variables by placing them where we would normally place data. For example, last lesson we learned to use print like this:\
`print("Hello!")`\
If we wanted to print the value of the variable named welcome, we would just use:\
`print(welcome)`\
This would print the value of the variable.

### Why do we use variables?

Variables allow us to use different values as our code is run and pass data in between different functions. We will use this more in the future.\
For now, we can use variables to organize our code and to make it more easy to read. This will become much more important once we start creating larger programs. For example:
```
greeting = "Welcome to the website"

print(greeting)
```
This would allow us to just change the value of greeting at the top rather than having to change it in the print function. When programs get longer, this will mean we won't have to search for a function to update the value manually and can just update it at the top.