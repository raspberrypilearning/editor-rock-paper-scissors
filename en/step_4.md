<h2 class="c-project-heading--task">Add line breaks</h2>
### Step 1

The code uses numbers to get the computer's choice.


### Step 2

The computer's choice gets printed on a new line. 

You can fix that by adding `end=' '` after `vs`

That tells Python to end with a space instead of a new line.


<div class="c-project-code">
--- code ---
---
language: python
filename: main.py
line_numbers: true
line_number_start: 3
line_highlights: 4
---
player = input('Choose rock (r), paper (p) or scissors (s)')
print(player, 'vs', end='')

chosen = randint(1,3) # Generate a random number between 1 and 3
# print(chosen)
--- /code ---
</div>

<div class="c-project-output">
<pre>Choose rock (r), paper (p) or scissors (s)
r vs p</pre>
</div>
