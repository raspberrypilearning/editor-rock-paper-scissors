<h2 class="c-project-heading--task">Challenge</h2>

Add emojis to your game!

## Step 1

Instead of using the letters r, p, and s to represent rock, paper, and scissors, try adding emojis.

+ Rock could be 🪨 or ✊
+ Paper 📄 or ✋
+ Scissors ✂️ or ✌️

## Step 2

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

## Step 3

Then add to the computer `chosen` options, below shows how to do this for rock. Try adding paper and scissors too.


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

## Now run your code

Run your code and check that the choices and result are shown with emojis.
