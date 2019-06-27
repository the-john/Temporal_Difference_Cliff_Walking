# Temporal_Difference_Cliff_Walking

The agent moves through a  4×12  gridworld, with states numbered as follows:

[[ 0,  1,  2,  3,  4,  5,  6,  7,  8,  9, 10, 11],
 [12, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23],
 [24, 25, 26, 27, 28, 29, 30, 31, 32, 33, 34, 35],
 [36, 37, 38, 39, 40, 41, 42, 43, 44, 45, 46, 47]]
At the start of any episode, state 36 is the initial state. State 47 is the only terminal state, and the cliff corresponds to states 37 through 46.

The agent has 4 potential actions:

UP = 0
RIGHT = 1
DOWN = 2
LEFT = 3
Thus,  +={0,1,…,47} , and  ={0,1,2,3} .

What we are trying to do is build the optimal policy for the Cliff Walking environment described above.

This Jupyter Notebook has sample code that uses:
- Sarsa Temporal Difference Control
- Q-Learning Temporal Difference Control
- Expected Sarsa TEmporal Difference Control

There is some Python test code to make sure things are working as expected, and can be found here [check_test.py](https://viewsyedytqpmq.udacity-student-workspaces.com/edit/check_test.py).

To help plot some of this code's output, I use [plot_utils.py](https://viewsyedytqpmq.udacity-student-workspaces.com/edit/plot_utils.py).
