<h2 class="c-project-heading--task">Add line breaks</h2>
--- task ---
The code uses numbers to get the computer's choice.
--- /task ---

--- task ---
The computer's choice gets printed on a new line. 

You can fix that by adding `end=' '` after `vs`

That tells Python to end with a space instead of a new line.
--- /task ---

<div class="c-project-code">
--- code ---
---
language: python
filename: main.py
line_numbers: true
line_number_start: 7
line_highlights: 7
---
print('vs', end=' ')

chosen = randint(1,3)
#print(chosen)
--- /code ---
</div>