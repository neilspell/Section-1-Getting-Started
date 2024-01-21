# Escape Sequences

Let’s say we wanted to display the following text exactly – including the quotation marks. 

*In the words of Nelson Mandela, “Education is the most powerful weapon which we can use 
to change the world”*

## Instructions

The line below does not work because in the ‘eyes’ of Python the second quotation closes the first and the remainder of the line is not understood.
``print("In the words of Nelson Mandela, "Education is the most powerful weapon which we can use to change the world"")``


1. Try the code above for yourself in ``main.py`` and see what happens.

To fix the syntax error we escape the second quotation using the backslash character, ``\`` as follows:
```python
print("In the words of Nelson Mandela, \"Education is the most powerful weapon which we can use to change the world\"")
```
2. Type the code above into ``main.py`` and see if you can get it to output correctly.

In the above example the use of ``\`` tells Python include the double quotes as part of the string (as opposed to treating it as the closing quote).

3. Try the following in ``main.py``and *add comments* to explain what is happening:

````python
print("A\tB\nC")
print("C:\\Users\\johndoe\\Documents\\myfile.txt")
````





