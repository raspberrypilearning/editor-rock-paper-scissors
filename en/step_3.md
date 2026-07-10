## Print choice

The code uses numbers to get the computer's choice.

Use `if` and `elif` to make the chosen number rock, paper, or scissors.

  + 1 = rock (r)
  + 2 = paper (p)
  + 3 = scissors (s)

You can add a `#` to the start of the line `print(chosen)` to make the computer ignore this instruction.

```python filename="main.py" line_numbers="true" line_number_start="6" line_highlights="7,9-18"
chosen = randint(1,3) # Generate a random number between 1 and 3
# print(chosen)

if(chosen == 1):
    computer = 'r' # Computer picks rock

elif(chosen == 2):
    computer = 'p' # Computer picks paper

elif(chosen == 3):
  computer = 's'# Computer picks scissors

print(computer)
```

## Now run your code

Try it a few times to see the letter change.

Click **Run** a few times and check that the computer prints `r`, `p`, or `s` to match its random choice.

```
Choose rock (r), paper (p) or scissors (s)
s vs
r
```
