## The year 2035

You can also do calculations and print numbers. Let's find out how old you'll be in the year 2035!

To calculate how old you'll be in the year 2035, you need to subtract the year you were born from 2035.

--- task ---

Add this code to your program:

--- code ---
---
language: python
filename: main.py
line_numbers: true
line_number_start: 1
line_highlights: 9
---
print('Hi, I can code in Python!')

print('''
here's a picture of a dog:
o____ 
 ||||
 ''')

 print(2035 - 2015)
--- /code ---

--- /task ---

Notice that you don't need to put quotes around numbers. 

(You'll need to change the number `2015` if you were born in a different year.)

--- task ---

Click **Run**, and your program should print your age in the year 2035.

--- /task ---

--- task ---

You could improve your program by using `input()` to ask the user their age and store it in a __variable__ called `born`.

--- code ---
---
language: python
filename: main.py
line_numbers: true
line_number_start: 1
line_highlights: 9-10
---
print('Hi, I can code in Python!')

print('''
here's a picture of a dog:
o____ 
 ||||
 ''')

born = input('What year were you born?')
print(2035 - born)
--- /code ---

--- /task ---

--- task ---

Run your program and then enter the year you were born. Did you get another error message?

That's because anything typed into your program is __text__, and it needs to be converted to a __number__.

You can use `int()` to convert the text to an __integer__. An integer is a whole number.

--- code ---
---
language: python
filename: main.py
line_numbers: true
line_number_start: 1
line_highlights: 10
---
print('Hello!')

print('''
here's a picture of a dog:
o____ 
 ||||
 ''')

born = input('What year were you born?')
born = int(born)
print(2035 - born)
--- /code ---

--- /task ---

--- task ---

You can also create another variable to store your calculation, and print that instead.

--- code ---
---
language: python
filename: main.py
line_numbers: true
line_number_start: 1
line_highlights: 11-12
---
print('Hello!')

print('''
here's a picture of a dog:
o____ 
 ||||
 ''')

born = input('What year were you born?')
born = int(born)
age = 2035 - born
print(age)
--- /code ---

--- /task ---

--- task ---

Finally, you can make your program easier to understand by adding a helpful message.

--- code ---
---
language: python
filename: main.py
line_numbers: true
line_number_start: 9
line_highlights: 12
---
born = input('What year were you born?')
born = int(born)
age = 2035 - born
print('In the year 2035 you\'ll be', age, 'years old!')
--- /code ---

--- /task ---




