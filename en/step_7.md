<h2 class="c-project-heading--task">Challenge</h2>
--- task ---

Add emojis to your game!

--- /task ---

Instead of using the letters r, p and s to represent **r**ock, **p**aper and **s**cissors, try adding emojis.

+ rock could be 🪨 or ✊
+ paper 📄 or ✋
+ scissors ✂️ or ✌️

--- task ---

Add a new line to each of the `chosen` options, below shows this for rock. Try adding for paper and scissors.

--- /task ---

<div class="c-project-code">
--- code ---
---
language: python
filename: 
line_numbers: true
line_number_start: 6
line_highlights: 11
---
chosen = randint(1,3) # Generate a random number between 1 and 3
#print(chosen)

if(chosen == 1):
    computer = 'r' # Computer picks rock
    print('🪨')
--- /code ---
</div>


