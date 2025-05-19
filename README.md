

**Q-Learning**: In Q-learning i simulated a situation where we had a table with states from 1 to 4 with 4 being the goal and then we had two possible actions for each state 
with a negative reward for each action and a posistive reward for getting to the treasure state. It uses the Bellman Equation to simulate learning and keeps updating which 
actions to take in order to get to the treasure state optimally.

**Deep Q-Network** : In DQN the idea is very similar to Q-Learning with the major difference being in how learning is done, here we learn by using a neural network where 
for each state we're in the network tries to either take a random action or predict which action to take based on how the network has learnt which action is better at that state, we 
do this until we get to the treasure state

**Policy Gradient Method** : In the PG method example i used the CartPole environment to show an understanding of the method. With the idea being similar to DQN and the difference
being that we are working with a probability distribution, we use the network here to update the probability distribution and the gradient ascent to adjust the policy
for each state and episode, this will make our reward, state and action move better. This process continues until we either run out of episodes, we exceed the game limitations or 
we get the maximum number of points(This indicates we've solved the problem)
