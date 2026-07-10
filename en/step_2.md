## Computer's turn

Now it's the computer's turn.

Use `randint` to generate a random number for the computer.

```python filename="main.py" line_numbers="true" line_number_start="3" line_highlights="6-7"
player = input('Choose rock (r), paper (p) or scissors (s)')
print(player, 'vs')

chosen = randint(1,3) # Generate a random number between 1 and 3
print(chosen)
```

## Now run your code

You'll need to enter 'r', 'p', or 's' each time.

Run your code a few times, enter `r`, `p`, or `s`, and check that the random number changes between `1`, `2`, and `3`.
