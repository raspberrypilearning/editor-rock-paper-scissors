## Add line breaks

The computer's choice gets printed on a new line.

You can fix that by adding `end=' '` after `vs`

That tells Python to end with a space instead of a new line.

```python filename="main.py" line_numbers="true" line_number_start="3" line_highlights="4"
player = input('Choose rock (r), paper (p) or scissors (s)')
print(player, 'vs', end=' ')

chosen = randint(1,3) # Generate a random number between 1 and 3
# print(chosen)
```

## Now run your code

Run your code and check that your choice and the computer choice appear on the same line, such as `r vs p`.

```
Choose rock (r), paper (p) or scissors (s)
r vs p
```
