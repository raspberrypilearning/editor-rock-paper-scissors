<h2 class="c-project-heading--task">Check the result</h2>

Check the player choice *and* the computer choice using `and`.

<h2 class="c-project-heading--explainer">Follow these instructions</h2>

## Step 1

+ If they are the same then it is a draw
+ look for where the player chose 'r' (rock) but the computer didn't.
+ If the computer chose 's' (scissors) then the player wins (rock beats scissors). 
+ If the computer chose 'p' (paper) then the computer wins (paper beats rock).


<div class="c-project-code">
--- code ---
---
language: python
filename: main.py
line_numbers: true
line_number_start: 18
line_highlights: 20-39
---
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
--- /code ---
</div>

## Step 2

Play the game!

Click **Run** to start a new game. 

 
<div class="c-project-output">
<pre>Choose rock (r), paper (p) or scissors (s)
r
r vs r
DRAW!</pre>
</div>

## Now run your code

Confirm the observable result.
