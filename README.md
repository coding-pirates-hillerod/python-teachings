# Python teachings
This repo is meant as a place to write down a somewhat more concrete and structured "plan" for teaching kids how to program in Python.

## Teaching plan
These (hopefuly quite concrete) thoughts about teaching kids Python are structured in a sort of "teachings per evening" so that it'll hopefully be more managable to teach the kids about this topic.

The below "teaching plan" is, therefore, not thought of as a plan that absolutely need to follow step by step in order to teach kids Python. The general idea is more that this plan can be used as way of more easily getting started teaching kids about Python.

In short: do whatever you like and if people can use this repo for inspiration then .. great.

### Evening #1
As kids probably won't be interested in hearing about stuff like "Python was developed by a guy named Guido van Rossum and .. blah, blah, blah", then it might be a good idea to get them started by following these topics for starters.

#### Start with a minor session of "show and tell" (Est. time: 10-15 min)
But before diving straight into coding it could be wise to both ask and show them what Python is, how we write it and what we can do with it. Perhaps like this:
1. Ask them what a programming language is (to get them to think about that - at least)
2. Show them that it's just some weird language we write in an IDE that tells the computer to do as we say
3. Show them what one can do with Python (like code some stuff, obviously, create games, automate stuff, web scrape stuff and so on

#### Download Python and VS Code (Est. time: 20 min.)
From this - hopefully good - starting point one would obviously need to get the kids to download the following so that they can start coding:
1. Download Python
2. Download VS Code

#### Install VS Code Extensions (Est. time: 10 min)
After having downloaded Python and VS Code make the kids download the following extensions for syntax help and easily running code:
1. Python (by Microsoft)
2. Code Runner

#### Show and tell of how to code (Est. time: 10 min)
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

##### Exercise: Make the kids code a simple 'Hello, World!' program (Est. time: 5 min)
Having shown the kids how to setup, write and execute Python code in VS Code, then have them code their own version of a 'Hello, World!' program. If they wanna print 'Hello, Mom!' instead, well, then fine - let them do whatever they like.

#### Show and tell how mulitple line statement execution works (Est. time: 5-10 min)
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

##### Excercise: Make the kids execute multiple lines of code (Est. time: 5 min)
Having shown the kids how mulitple lines of code executen then have them do the same.

#### Show and tell how variables work (Est. time: 5 min)
Show the kids various types of variables like:
```python
name = "Mogens"
age = 80
money 12345.678
is_cool = True

print(f"Hi, my name is {name} and I'm {age} years old and have {money} in the bank. And I'm totally cool right!? {is_cool} ")
```

##### Exercise: Make the kids play around with variables (Est. time: 5 min)
Let the kids use what variables they want and have them play around creating sentences using the "f-string".

#### Show and tell: The 'input' function
As the kids have now learned about variables then show them how Python's 'input' function work. Here's an example:
```python
name = input("Hi, what's your name? ")
print(f"Nice to meet you {name}!")
```

##### Exercise: Play with the 'input' function
Well .. let the kids play around with the 'input' function.


