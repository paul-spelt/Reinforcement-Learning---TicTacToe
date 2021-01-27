# Reinforcement-Learning---TicTacToe
TicTacToe Robot created for self-learning<br>
This robot plays N games of TicTacToe against itself as p1 and p2<br>
The winner of each game is rewarded and the reward is propagated through the historical board states<br>
This leads to a State:Value dictionary which is used to guide policy decisions<br>
The robot will balance exploration-exploitation using an epsilon-greedy method<br>
After training a human can play against the robot<br>
In it's current state with N=50,000 games the robot will always win or force a draw<br>


