<h2 class="c-project-heading--task">Challenge</h2>
### Step 1

Add emojis to your game!


### Step 2

Instead of using the letters r, p and s to represent **r**ock, **p**aper and **s**cissors, try adding emojis.

+ rock could be 🪨 or ✊
+ paper 📄 or ✋
+ scissors ✂️ or ✌️


### Step 3

To do this, add `if` and `elif` to each of the `player` options, like the code below.

<div class="c-project-code">
--- code ---
---
language: python
filename: 
line_numbers: false
line_number_start: 
line_highlights: 
---
player = input('Choose rock (r), paper (p) or scissors (s)')
if(player == 'r'):
    print('🪨', end='')
    print('vs', end='')
--- /code ---
</div>


### Step 4

Then add to the computer `chosen` options, below shows this for rock. Try adding for paper and scissors.


<div class="c-project-code">
--- code ---
---
language: python
filename: 
line_numbers: false
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
