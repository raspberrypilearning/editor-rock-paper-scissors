<h2 class="c-project-heading--task">Computer's turn</h2>

Now it's the computer's turn.

## Step 1

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

## Step 2

**Run** your code lots of times to check that it prints 1, 2, or 3 randomly. 

You'll need to enter 'r', 'p', or 's' each time.

## Now run your code

Run your code a few times, enter `r`, `p`, or `s`, and check that the random number changes between `1`, `2`, and `3`.
