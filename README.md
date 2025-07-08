# Actor-Critic Methods on Lunar Lander & Bipedal Walker

Actor-Critic methods are high-performing agents that combine the best aspects of simpler RL models. To demonstrate our reinforcement learning skills, my teammate and I built the A2C agent from scratch and tested its performance on the Lunar Lander and Bipedal Walker gymnasium environments.

Skills:

PyTorch, multi-threading, hyperparameter tuning, gradient ascent

Environment:
- Cart Pole from Gymnasium ([link](https://gymnasium.farama.org/environments/classic_control/cart_pole/))
- Lunar Lander from Gymnasium ([link](https://gymnasium.farama.org/))
- Bipedal Walker from Gymnasium ([link](https://gymnasium.farama.org/environments/box2d/bipedal_walker/))

Methodology:
- Built an actor-critic agent from scratch and evaluated on Cart Pole
- Improved the agent to an A2C agent by adding synchronous multi-threading
- Evaluated agent on Lunar Lander and Bipedal Walker environments

Tools & Technologies:
- Programming Language: Python
- Libraries: pytorch, gymnasium, multiprocessing, matplotlib
- Software: Jupyter Notebook, Github

Results & Evaluation:

The A2C agent was able to learn an optimal policy and solve the Lunar Lander environment by earning a reward above 200 points. While the agent may not have reached the best policy with the Bipedal Walker environment, the agent showed strong convergence and promising improvement across episodes. 

Challenges & Learning:

I learned how to implement multiple threads for a multi-processing model to make effective use of computational resources. This project significantly improved my skills at tuning hyperparameters for reinforcement learning tasks.

Contribution:
- Team Members: Erin Gregoire & John Abramo
- My Role: Evaluated the base actor-critic model on Cart Pole, co-built the A2C model, and evaluated the A2C model on Lunar Lander
