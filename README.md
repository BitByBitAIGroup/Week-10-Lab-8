# Week-10-Lab-8
Demonstration of  Matchbox Educable Noughts and Crosses Engine(MENACE)
# Problem Statement
Read the reference on MENACE by Michie and check for its 
implementations. Pick the one that you like the most and go through the 
code carefully. Highlight the parts that you feel are crucial. If possible, try 
to code the MENACE in any programming language of your liking.

# MENACE
MENACE stands for Machine Educable Noughts 
and Crosses Engine [1]. It was originally 
described by Donald Michie, 
who used 304 matchboxes to record each game 
he played against this algorithm.
 This provides an adequate conceptual basis for a 
trial-and-error learning device, provided that the 
total number of choice-points which can be 
encountered is small enough for them to be 
individually listed. Michie’s aim was to prove 
that a computer could ”learn” from failure and 
success to become good at a task.

# MENACE Strategy and The working of the 
Learning Model
MENACE (Machine Educable Noughts And Crosses Engine) is a learning model used to teach a computer to 
play noughts and crosses. The model is based on a reinforcement learning approach and uses a series of 
plastic beads to represent the possible moves available to the computer player. These beads are distributed 
amongst a series of boxes, corresponding to the different possible board configurations. When the computer 
moves, it picks a box with beads in it at random and selects a move corresponding to the bead's position in 
the box. **If the move leads to a win, the beads in that box are rewarded by adding additional beads of 
the same color. If the move leads to a loss, the beads are punished by removing beads of that color.** With 
enough training, the beads in each box come to represent the optimal move for that board configuration, and 
the computer becomes unbeatable.<br><br>
![image](https://user-images.githubusercontent.com/91957156/227187990-150751c2-becb-4d4a-9fe1-71a6c0a55896.png)<br>
●MENACE lost the game above, so the beads that were chosen are removed from the boxes.
This means that MENACE will be less likely to pick the same colours again and has learned. <br>
● If MENACE had won, three beads of the chosen colour would have been added to each box, 
encouraging MENACE to do the same again.<br>
● If a game is a draw, one bead is added to each box<br>

# Observations
●The Menace game demonstrated the power of reinforcement learning in training a 
machine to play a simple game like tic-tac-toe without explicit programming of the 
rules.<br>
● Menace used a simple neural network consisting of matchboxes filled with colored 
beads to represent different states of the game and the moves that Menace could 
make. The beads were used to encode the machine's learning and decision-making 
process.<br>
● Menace was trained through a process of trial and error, where the machine played 
against itself and learned from its mistakes. The reinforcement signal was provided by 
the beads in the matchbox<br>
![image](https://user-images.githubusercontent.com/91957156/227188694-f5f8e98b-7b7a-44f0-bc27-0bcbf950603f.png)
# Results<br>
If player 1 and player 2 are playing 
game then if player 1 takes first turn then 
winning probability of 
player 1 : player = 2:1
<br><br>
![image](https://user-images.githubusercontent.com/91957156/227188887-0558d461-7281-48a8-bce7-6787da576eff.png)<br>
The progress of MENACE’S maiden tournament 
against a human opponent. The line of dots 
drops one level for a defeat, rises one level 
for a draw and rises three levels for a victory. 
Refer the following Figure.
<br>
### Trained MENACE<br><br>
![image](https://user-images.githubusercontent.com/91957156/227189046-44562909-a96e-4df4-ade3-2e6d5909441e.png)<br><br>
For Trained MENACE,When MENACE plays a 
perfect-playing computer, 
the results look like this:
The Red colour symbolises 
that most of the games 
were draw!<br>
![image](https://user-images.githubusercontent.com/91957156/227189221-017a1f86-0468-48ed-bcae-21e3c7b950af.png)<br><br>
When MENACE played a with a 
random picking opponent, the 
result is a near-perfect 
positive correlation





