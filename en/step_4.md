## ASCII art

Let’s print something much more fun than text: ASCII art! ASCII art (pronounced '_ask-e_') is creating __pictures out of text__.

--- task ---

Let's add some art to your program — a picture of a dog!

--- code ---
---
language: python
filename: main.py
line_numbers: true
line_number_start: 1
line_highlights: 3-5
---
print('Hi, I can code in Python!')

print('here's a picture of a dog:')
print('o____ ')
print(' |||| ")
--- /code ---

--- /task ---

The dog's legs are made using the pipe character `|` which you can type by pressing <kbd>Shift + \ </kbd> on most UK/US English keyboards. 


If you click **Run**, you'll see that there's a bug in your new code.


That's because your text contains an apostrophe `'`, which Python thinks is the end of the text!

--- task ---

To fix this, just put a backslash `\` before the apostrophe in the word `here's`. 

This tells Python that the apostrophe is part of the text.

--- code ---
---
language: python
filename: main.py
line_numbers: true
line_number_start: 1
line_highlights: 3
---
print('Hi, I can code in Python!')

print('here\'s a picture of a dog:')
print('o____ ')
print(' |||| ")
--- /code ---
--- /task ---

If you prefer, you can use three apostrophes `'''` instead of one, which allows you to print multiple lines of text with one `print` statement:

--- code ---
---
language: python
filename: main.py
line_numbers: true
line_number_start: 1
line_highlights: 3-7
---
print('Hi, I can code in Python!')

print('''
here's a picture of a dog:
o____ 
 ||||
 ''')
--- /code ---
