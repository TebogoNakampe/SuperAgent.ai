# SuperAgent.ai
Q- Machine Learning in UNITY3D
This Project was inspired by UNITY Technologies Q-GridWorld Project:
https://github.com/Unity-Technologies/Q-GridWorld

The goal when doing Reinforcement Learning is to train an agent which can learn to act in ways that maximizes future expected rewards within a given environment. In the last post in this series, that environment was relatively static. The state of the environment was simply which of the three possible rooms the agent was in, and the actions were choosing which chest within that room to open. Our algorithm learned the Q-function for each of these state-action pairs: Q(s, a). This Q-function corresponded to the expected future reward that would be acquired by taking that action within that state over time. 

To test on your local machine, please got to the superagent folder and run the application

InternalAgent.cs contains all of the Q-learning logic.
GridEnvironment.cs contains all of the environment-specific logic.
