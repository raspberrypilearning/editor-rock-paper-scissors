## Check the result

Check the player's choice **and** the computer's choice using `and`.

+ If they are the same then it is a draw
+ Look for where the player chose 'r' (rock) but the computer didn't
+ If the computer chose 's' (scissors) then the player wins (rock beats scissors)
+ If the computer chose 'p' (paper) then the computer wins (paper beats rock)

```python filename="main.py" line_numbers="true" line_number_start="18" line_highlights="20-39"
print(computer)

if(player == computer):
    print('DRAW!') 

elif(player == 'r' and computer == 's'):
    print('Player wins!')
  
elif(player == 'r' and computer == 'p'):
    print('Computer wins!')

elif(player == 'p' and computer == 'r'):
    print('Player wins!')
  
elif(player == 'p' and computer == 's'):
    print('Computer wins!')

elif(player == 's' and computer == 'r'):
    print('Computer wins!')

elif(player == 's' and computer == 'p'): 
    print('Player wins!')
```

## Now run your code

Play the game!

Click **Run** and check that the game now tells you whether it is a draw, a player win, or a computer win.

```
Choose rock (r), paper (p) or scissors (s)
r
r vs r
DRAW!
```
