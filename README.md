# Reinforcement-Learning---TicTacToe
TicTacToe Robot created for self-learning
This robot plays N games of TicTacToe against itself as p1 and p2.
The winner of each game is rewarded and the reward is propagated through the historical board states.
This leads to a State:Value dictionary which is used to guide policy decisions.
The robot will balance exploration-exploitation using an epsilon-greedy method.
After training a human can play against the robot.
In it's current state with N=50,000 games the robot will always win or force a draw.


