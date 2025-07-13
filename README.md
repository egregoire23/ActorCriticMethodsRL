# Actor-Critic Methods on Classic Gym Environments

Actor-Critic methods are powerful reinforcement learning agents that combine the strengths of value-based and policy-based models. To demonstrate our reinforcement learning skills, my teammate and I built an Actor-Critic agent from scratch and evaluated it on the CartPole environment. We then enhanced the model into an A2C (Advantage Actor-Critic) agent using synchronous multi-threading and tested its performance on the LunarLander and BipedalWalker environments from Gymnasium.

Skills:

PyTorch, Multi-Threading, Hyperparameter Tuning, Gradient Ascent

Environment:
- Cart Pole from Gymnasium ([link](https://gymnasium.farama.org/environments/classic_control/cart_pole/))
- Lunar Lander from Gymnasium ([link](https://gymnasium.farama.org/))
- Bipedal Walker from Gymnasium ([link](https://gymnasium.farama.org/environments/box2d/bipedal_walker/))

Methodology:
- Built a base Actor-Critic agent and evaluated it on CartPole
- Upgraded the model to A2C with synchronous multi-threading
- Evaluated the A2C agent on LunarLander and BipedalWalker environments

Tools & Technologies:
- Programming Language: Python
- Libraries: pytorch, gymnasium, multiprocessing, matplotlib
- Software: Jupyter Notebook, Github

Results & Evaluation:

The base Actor-Critic model consistently solved the CartPole environment by achieving maximum reward across evaluation episodes. The enhanced A2C agent successfully learned an optimal policy on LunarLander, averaging rewards above 200. While the agent did not fully solve BipedalWalker, it demonstrated strong learning and consistent improvement across episodes.

Challenges & Learning:

I learned how to implement multi-threaded training using multiprocessing to improve training efficiency. This project also strengthened my ability to tune hyperparameters in reinforcement learning and understand the intricacies of stabilizing learning in actor-critic architectures.

Contribution:
- Team Members: Erin Gregoire & John Abramo
- My Role: Evaluated the base Actor-Critic model on CartPole, co-developed the A2C model, and evaluated its performance on LunarLander
