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

## Show and tell: Type casting
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
