# Keras-rl_DQN-
Create a deep learning model to solve a OpenAI Gym Lunar Lander. <br>
0.Open the Lunar Lander environment from gym <br>
1.Build the deep learning model by keras Sequential API with Embedding and Dense layers <br>
2.Import the Epsilon Greedy policy and Sequential Memory deque from keras-rl2's rl <br>
3.input the model, policy, and the memory in to rl.agent.DQNAgent and compile the model and fit<br>
4.using wrappers to record videos to check the quaily of the training: agent.test(env,nb_episodes=10,visualize=False)<br>
5.Save the model's weight
