<h2 class="c-project-heading--task">Print choice</h2>
--- task ---
The code uses numbers to get the computer's choice.
--- /task ---

--- task ---
Use `if`, `elif` to check the chosen number with the rock, paper or scissors.

  + 1 = rock (r)
  + 2 = paper (p)
  + 3 = scissors (s)
--- /task ---

<div class="c-project-code">
--- code ---
---
language: python
filename: main.py
line_numbers: true
line_number_start: 10
line_highlights: 16-17
---
chosen = randint(1,3) # Generate a random number between 1 and 3
# print(chosen)

if(chosen == 1):
    computer = 'r'

elif(chosen == 2):
    computer = 'p'

elif(chosen == 3):
  computer = 's'

print(computer)
--- /code ---

--- task ---
Click **run** to print the letter that corrosponds to the random number.

You can add a `#` to the start of the line `print(chosen)`, to make the computer ignore it.
--- /task ---
</div>

  
