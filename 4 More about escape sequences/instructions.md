# More about special (escape) characters  
As you know, each key on a computer’s keyboard is assigned to a character e.g. letters, numerals, or other symbols. 

In Python strings, the backslash ``\`` is known as a special character, also called the escape character. In the previous example, we used ``\n`` to represent a new line. 

For a tab, we use ``\t``.

Adding two escape characters turns the backslash back into an ordinary character, e.g. ``\\`` prints a single ``\``. We can use these special characters to output different patterns. 

## PRIMM
1. Predict what the code below will output, write down and compare predictions.
2. Try typing the code below into ``main.py``:
````python
print("*********\n*\t*\n**\t*")
````
3. Was your prediction correct?


## Printing blank spaces
Blank spaces in strings are also regarded as characters. Let’s suppose we want to have a blank space between each asterisk in the top line of the output in the previous example.

1. Add blank spaces to the code above to see what changes will occur.
2. Experiment further to create different patterns of your own such as a square,
   triangular shape or even a circle.

## Printing Numbers
Python recognises when numeric symbols are being used as numbers rather than as strings of text. For numbers, we do not use quotation marks. 
Python can do calculations on numbers used in a ``print()`` function. 

Run the following code in ``main.py``:
````python
print(5)
print(5+7)
````
Note: The calculation takes precedence over the display instruction, in a 
similar way to the order of operations in maths *(BIMDAS)*.


## Printing numbers and text together
If we want to print numbers and text together, we can include the number with the text as a string, or not.

## PRIMM
1. Predict what the code below will output, write down and compare predictions.
2. Try typing the code below into ``main.py``:
````python
# (a)
print("Answer: 25")

# (b) 
print("Answer: ",25)


````
3. Was your prediction correct?
4. Replace ``25`` with the mathematical operation ``25 - 10`` in each of the last two
   examples. Run each one and explain the difference in output.
