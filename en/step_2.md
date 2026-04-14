<h2 class="c-project-heading--task">Computer's turn</h2>
### Step 1

Now it's the computer's turn. 


### Step 2

Use `randint` to generate a random number for the computer.


<div class="c-project-code">
--- code ---
---
language: python
filename: main.py
line_numbers: true
line_number_start: 3
line_highlights: 6-7
---
player = input('Choose rock (r), paper (p) or scissors (s)')
print(player, 'vs')

chosen = randint(1,3) # Generate a random number between 1 and 3
print(chosen)
--- /code ---
</div>
### Step 3

**Run** your code lots of times to see random number either 1, 2 or 3. 

You'll need to enter 'r', 'p' or 's' each time.
