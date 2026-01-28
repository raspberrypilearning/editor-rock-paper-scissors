<h2 class="c-project-heading--task">Challenge</h2>
--- task ---

Add emojis to your game!

--- /task ---

Instead of using the letters r, p and s to represent **r**ock, **p**aper and **s**cissors, try adding emojis.

+ rock could be 🪨 or ✊
+ paper 📄 or ✋
+ scissors ✂️ or ✌️

--- task ---

To do this, add `if` and `elif` to each of the `player` options, like the code below.

--- /task ---

<div class="c-project-code">
--- code ---
---
language: python
filename: 
line_numbers: true
line_number_start: 
line_highlights: 
---
player = input('Choose rock (r), paper (p) or scissors (s)')
if(player == 'r'):
    print('🪨 vs', end=' ')

--- /code ---
</div>


--- task ---

Then add to the computer `chosen` options, below shows this for rock. Try adding for paper and scissors.

--- /task ---

<div class="c-project-code">
--- code ---
---
language: python
filename: 
line_numbers: true
line_number_start: 
line_highlights: 
---
chosen = randint(1,3) # Generate a random number between 1 and 3
# print(chosen)

if(chosen == 1):
    computer = 'r' # Computer picks rock
    print('🪨')
--- /code ---
</div>

