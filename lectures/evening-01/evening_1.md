# Evening #1
As kids probably won't be interested in hearing about stuff like "Python was developed by a guy named Guido van Rossum and .. blah, blah, blah", then it might be a good idea to get them started by following these topics for starters.

## Start with a minor session of "show and tell" (Est. time: 10-15 min)
But before diving straight into coding it could be wise to both ask and show them what Python is, how we write it and what we can do with it. Perhaps like this:
1. Ask them what a programming language is (to get them to think about that - at least)
2. Show them that it's just some weird language we write in an IDE that tells the computer to do as we say
3. Show them what one can do with Python (like code some stuff, obviously, create games, automate stuff, web scrape stuff and so on

## Download Python and VS Code (Est. time: 20 min.)
From this - hopefully good - starting point one would obviously need to get the kids to download the following so that they can start coding:
1. Download Python
2. Download VS Code

## Install VS Code Extensions (Est. time: 10 min)
After having downloaded Python and VS Code make the kids download the following extensions for syntax help and easily running code:
1. Python (by Microsoft)
2. Code Runner

## Show and tell of how to code (Est. time: 10 min)
By having everything set up, then first show the kids how to code in VS Code by:
1. Open VS Code
2. Use the 'open folder' button to create a new folder as a workspace for their code
3. Create a 'main.py' file
4. Write some code - preferably just a single statement using the 'print' function
5. Show how to execute the code by using the "run" button provided by 'Code Runner'

A code example of this process could just be something like executing the classic "Hello, World!" program like this:
```python
print("Hello, World!")
```

### Exercise: Make the kids code a simple 'Hello, World!' program (Est. time: 5 min)
Having shown the kids how to setup, write and execute Python code in VS Code, then have them code their own version of a 'Hello, World!' program. If they wanna print 'Hello, Mom!' instead, well, then fine - let them do whatever they like.

## Show and tell how mulitple line statement execution works (Est. time: 5-10 min)
In order for the kids to understand how coding really works, then it might just be a good idea to show them how the Python interpreter executes code line by line.

Hence, one might first show them how these 2 lines of code gets executed one after the other:
```python
print("Hello,")
print("World!")
```

And afterwards show them what happens when one reverses the order of execution of the same 2 lines:

```python
print("World!")
print("Hello,")
```

### Excercise: Make the kids execute multiple lines of code (Est. time: 5 min)
Having shown the kids how mulitple lines of code executen then have them do the same.

## Show and tell how variables work (Est. time: 5 min)
Show the kids various types of variables like:
```python
name = "Mogens"
age = 80
money 12345.678
is_cool = True

print(f"Hi, my name is {name} and I'm {age} years old and have {money} in the bank. And I'm totally cool right!? {is_cool} ")
```

### Exercise: Make the kids play around with variables (Est. time: 5 min)
Let the kids use what variables they want and have them play around creating sentences using the "f-string".

## Show and tell: The 'input' function (Est. time: 5 min)
As the kids have now learned about variables then show them how Python's 'input' function work. Here's an example:
```python
name = input("Hi, what's your name? ")
print(f"Nice to meet you {name}!")
```

### Exercise: Play with the 'input' function (Est. time: 5 min)
Well .. let the kids play around with the 'input' function.

## Show and tell: The 'len' function (Est. time: 5 min)
In order to get the kids to understand that Python comes with a lot of functions "baked in" then show them how another built-in function like the 'len' function can be used in Python.

Here's a simple example of how one could show that:
```python
name = input("Hey! what's your full name? ")
print(f"Wauw .. your name contains {len(name} characters! How 'awesome' is that .. ;P ")
```

### Exercise: Try the 'len' function (Est. time: 5 min)
With the above example in mind then just let the kids play around with the 'len' function how they like.

## Show and tell: The 'range' function (Est. time: 5 min)
In order to show the kids another useful built-in function then show them how the 'range' function work.

Here's an example:
```python
print("Tæl fra 1 til 9")
for i in range(0, 10):
  print(f"{i} ..")
```

### Exercise: Count from 1 to 99 (Est. time: 5 min)
Based on this 'show and tell' of how to count from 1 to 0 then make the kids do the same but from 1 to 99.

## Kids Exercise Time: Find and use a built-in function that rounds numbers

### Step #1
First of all, show the kids how they can easily find which built-in Python functions exists by doing a Google search on the term 'python built-in functions'.

### Step #2
From the results page show the correct link to Python's documentation that has an overview of all built-in functions.

### Step #3
Get the kids to do the following:
1. Create a variable called "number" and assign this the value of 2.675 thats rounded to only **1** decimal
2. Print the result of the rounded number

### Solution
The solution is as simple as:
```python
number = round(2.675, 1)
print(number)
```
