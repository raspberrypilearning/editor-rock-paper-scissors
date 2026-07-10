## Player's turn

Get the player's input for Rock, Paper, or Scissors.

Ask the player to choose rock, paper, or scissors by typing the letter 'r', 'p', or 's'.

Then `print` out what the player chose.

```python filename="main.py" line_numbers="true" line_number_start="1" line_highlights="3-4"
from random import randint
  
player = input('Choose rock (r), paper (p) or scissors (s)')
print(player, 'vs')
```

> [!TIP]
> Try adding to the `input()` message with your own text or use emojis.

## Now run your code

Click **Run** and check that the game asks you to choose rock, paper, or scissors.

```
Choose rock (r), paper (p) or scissors (s)
```
