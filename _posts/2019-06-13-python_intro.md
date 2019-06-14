---
layout: post
title: Python Intro Part 1
subtitle: I know English, but why is there a snake?
#gh-repo: daattali/beautiful-jekyll
#gh-badge: [star, fork, follow]
tags: [python, beginner, aliens, intro to python]
bigimg: /img/python_lang1.jpg
comments: true
---

Like Indiana Jones said while on his many adventures, why did it have to be snakes? Before being here, I had heard about Hyper Text Markup Language, Cascading Style Sheets, and some sets of letters with some symbols after them that could be musical or mathematical in notation. I liked to think that I knew about computers since I was a kid because I could troubleshoot any problem my mom had when we had an old Gateway computer that looked like a cow somehow leased it's prints to be on hardware. Little did I know that there is a huge difference between a user interface and programming code.

After spending some time doing some graphic design and working up to web design did I realize that there is a completely different world outside of the matrix. I didn't have the courage or experience like Neo and I took the blue pill to keep myself hidden from the overwhelming world that is programming. Fast forward 9 years and now I'm facing my fears.

It's really not so bad. It's as close to English as I can get in most respects.
```python
print("Hello World!")
```
This is me telling python to output ```Hello World```. You should see some of those mathematical music languages. It's definitely not that easy. It's also fairly intuitive as long as you know what you're doing.
```python
a = 1
avariable = 1.0
a_variable = "one"
```
Variables can be anything you want them to be without even being explicit about it. You don't have to tell them they have to be an integer, float, or string first and then put in the value. Just do it all at once.
```python
a = 1
a = 1.0
a = 'one'
```
Don't be a dummy though. Variables can be overwritten just as easily. So it's not going to be ```1``` or ```1.0``` when the last instruction is to call it ```one```. 
```python
list = []
dictionary = {}
still_parenthesis_and_also_a_tuple_but_also_method_calls = ()
```
This can be a little different than some other languages based on the usage, but it's important to know where they stand. Be wary of words that are used as built-in functions and methods because ```python list``` is blue for a reason. Also remember to use parentheses appropriately because it can get bunchy.
```python
def function():
  x = "It's that easy!"
  return x
```
Oh yeah, that's how a function is written, it really is that easy. By the way, it prints out with the quotes when the function is formed without a print function. ```"It's that easy!"```
```python
def next_function():
  x = "This one is too!"
  return print(x)
```
This next function returns a string without the quotes because of the print function. Typically useful for displaying strings.```This one is too!```
```python
x = 'oreos'
oreos_sleeve = ['i', 'will', 'eat', 6, x]
print(*oreos_sleeve)
```
With the asterisk in front of the list variable this prints out all the values with a space in between and no quotes.
```i will eat 6 oreos```
A fun part of lists is the use of multiple types of inputs inside the brackets and still being able to function.

Python is a great start to truly gain my confidence in the skill of a computer programming language. While plain, the fundamental rules are great to build an understanding upon, while keeping complexity to the more complex usage that we find in many python libraries.

  
