# Evening #2
Based on the first evening of teaching, this second evening will go through the following:
1. Type casting
2. Strings
3. etc (for now ..)

## Show and tell: The 'type' function (Est. time: 5 min)
As the 1st evening covered variables, data types and a brief walkthrough of some of Python's built-in functions it might just be wise to show the kids something about the built-in 'type' function as this would naturally spill over into the next topic of 'type casting'

Hence, an example of the 'type' could be this:
```python
integer = 10
print(type(integer))

decimal = 20.75
print(type(decimal))

text = "Hey .. I'm of the data type 'string'"
print(type(text))

boolean = True
print(type(boolean))
```

### Exercise: Play around with the 'type' function (Est. time: 5 min)
Just let the kids play around with the 'type' function.

## Show and tell: Type casting (Est. time: 5 min)
Now that the kids know about the 'type' and, therefore, should have a somewhat better understanding of the various data types in Python, it would probably be good to show them how one does 'type casting' in Python.

And so, here's some examples:
```python
number = "10"
print(int(number))

money = 1000
print(f"I have {str(money)} dollars in the bank!!")

to_decimal = 150
print(float(to_decimal))
```

### Exercise: Play around with the 'type casting' (Est. time: 5 min)
Do like the header says ..

## Show and tell: Strings pt. 1 - single and double quotes
For starters just tell the kids about how strings in Python is just text between quotes - double and single (but not mixed).

Here's an example:
```python
doubble_quotes = "This is a string with double quotes"
single_quotes = 'This is a string with single quotes'

print(doubble_quotes, single_quotes)
```

Based on that example, show the kids that a mixture of double and single quotes doesn't work:
```python
mixed_text = "This will not work'

print(mixed_text)
```

### Exercise: Play around with double and single quotes
Like the header says ..

## Show and tell: Strings pt. 2 - slicing
Just show the kids that strings can be sliced in many ways:
```python
text = "Min mor hedder Ole.."

print("From start until index")
print(text[:5])

print("\nFrom index til end")
print(text[3:])

print("\nNegative slicing")
print(name[:-5])
```

### Exercise: Slice your own name
Just something like:
```python
name = "Pelle KLumpfeber"
print(name[:6])
```

## Show and tell: Strings pt. 3 - string methods
Just show and tell the kids that one can use on strings by use of "dot notation". Some examples are shown below:

**Make stuff uppercase - upper()**
```python
name = input(WHat is your name? ")
print(name.upper())
```

**Remove whitespace - strip()**
```python
text = "  I have to many whitespaces ..     "
print(text.strip())
```

**Split text - split()**
```python
todos = " "Do the dishes, Take out the trash, Walk the dog"
print(todos.split(","))
```

### Exercise: Split and strip a list of todos
Given a list of 'todos' in one long string format with too many whitespaces, make the kids try to figure out how to first trim the text and then split it.

Solution:
```python
todos = "   Do the dishes, Take out the trash, Walk the dog    "
print(todos.trim().split(",))
```



