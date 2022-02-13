---
layout: default
title: For Loops
parent: Tutorial
nav_order: 5
---
# **An Introduction to For Loops**

### What is a For Loop?

Normally, our code runs from top to bottom. For example, in the example:
```
name = "Joe"

print(name)

name = "Bill"

print(name)
```
It would first output "Joe", then "Bill" in that order.\
Loops allow us repeat parts of code as many times as we'd like which is very important for many programs.

### How do we use For Loops?

In Python, we use "for i in range(number_of_loops):" then the code to repeat on the next line, indented once, to use a for loop. For example:
```
for i in range(10):
    print("Hello!")
```
This code would print "Hello!" out 10 times since that is the number we told it to repeat in the paranthesis and the code on the next line says to print "Hello!"\
If we wanted it to print it out 100 times, it would be easy to modify since we would just have to change the 10 to 100:
```
for i in range(100):
    print("Hello!")
```
Try making it print 1000 times, and see if it works!