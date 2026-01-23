<h2 class="c-project-heading--task">Player's turn</h2>
--- task ---
Let the player choose Rock, Paper or Scissors. 
--- /task ---

--- task ---
First, let the player choose Rock, Paper or Scissors by typing the letter 'r', 'p' or 's'. 

Then `print` out what the player chose.
--- /task ---

<div class="c-project-code">
--- code ---
---
language: python
filename: main.py
line_numbers: true
line_number_start: 1
line_highlights: 3-4
---
from random import randint
  
player = input('Choose rock (r), paper (p) or scissors (s)')

print(player, 'vs')
--- /code ---
--- task ---
Click **run** to test your code. 

You can add to the message with more text or use emojis.
--- /task ---  
</div>

<div class="c-project-output">
<pre>Choose rock (r), paper (p) or scissors (s)</pre>
</div>






