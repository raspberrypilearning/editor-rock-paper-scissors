<h2 class="c-project-heading--task">Print choice</h2>
--- task ---
The code uses numbers to get the computer's choice.
--- /task ---

--- task ---
Use `if` and `elif` to make the chosen number be rock, paper or scissors.

  + 1 = rock (r)
  + 2 = paper (p)
  + 3 = scissors (s)

You can add a `#` to the start of the line `print(chosen)`, to make the computer ignore it.
--- /task ---

<div class="c-project-code">
--- code ---
---
language: python
filename: main.py
line_numbers: true
line_number_start: 6
line_highlights: 9-18+
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
--- /task ---
</div>

output:
s vs
r
  
