# SoC_AI_Race_Cars
First Part(May):
Very ShortSummary of SoC AI-Race-Cars dated26/05/2022:

We first started with a course on Reinforcement Learning.
We learnt about Markov Processes and the terminology associated with the same.
We learnt about several methods of evaluating policies (like TDλ and TD(0) and MonteCarlo Evaluation).
Then we developed methods of comparing policies to arrive at the optimum policy.
Using the Bellman recursive relation we can update our policy as we move along iterations or at the end of an episode.
We then saw off-policy learning and took a general view of Model-free learning
The course concluded with a case study of some games which have been mastered by RL bots

We were learning to deal with Python libraries like matplotlib, numpy, OpenAIGym, tensorflow etc. 
We were using these libraries to build and run simple RL agents
We were mainly focusing on the Neural Network supported Q-Learning method of RL.
We were learning to run agents on self made as well as library environments.

We were coding stuff and playing around with RL


Middle Part(June):

Problem Description: An industrial plant degrades over time according to some function of time(varies with the stages). Determine the optimal policy which determines the optimal frequency of conducting maintainence on the plant given that the maintainence causes a negative reward.

Action Space: To conduct maintainence or to do nothing

This problem is inspired by a research paper (link attached in repo) and is conducted in 4 stages. Each of the 4 stages are solved usinng a simple Q-Learning Algorithm without the use of any Neural network.

Stage 1: The plant degrades with time. Maintainence incurs a small negative reward. Breakdown incurs a large negative reward. Regular operation grants positive reward per time step. Achieves research paper accuracy.

Stage 2: This time we provide the system with a measure of its current condition. The failure probability function is now modified to involve the condition variable c. It is a simple one-step complexification of the previous problem.

Stage 3: This is another one-step complexification of Stage 1- we simply make the reward decay after maintainence with time

Stage 4: This is a combination of stage 2 and 3 together.

All of these stages are solved using Reinforcement Learning by Q-Learning. The comparison of the Obtained result and the research estimate is linked in the repo.



Final Part(July):





