# Important terms about the RL to recall later

- RL is like trial and error
- It is completely different from the supervised or unsupervised learning, because in both of these, model learns from the given data, but in RL model learns by interaction.
  
## Important Terms

- Agent
- Environment
- State and Action
- Reward
- Markov Decision Process
  - Markov chain or sequence: state, transition probability
  - Markov Reward Process: Markov chain + Reward function
  - Markov Decision Process: MRP + Actions
- Action Space: set of all actions
  - Continuous 
  - Discrete 
- Policy: defines the agent's behaviour in the environment
  - Deterministic policy: maps to a specific action
  - Stochastic policy: maps to a probability distribution
    - Categorical policy
    - Gaussian policy
- Episode: interaction between an agent and the environment
- Episodic and Continuous tasks
  - Episodic: a task with a terminal state
  - Continuous: a task with no terminal state
- Horizon: time steps till which agent will interact with the environment
  - Finite horizon
  - Infinite horizon
- Return: total rewards obtained by an agent during an episode
  - In case of episodic tasks, reward calculation is simple
  - In case of continuous task, how will we do this calculation?
    - Discount factor comes to rescue in this case
    - Discount factor ranges from 0 to 1. A high discount factor means, we will give high importance to the future rewards, while a low discount factor means that we will give more importance to the immediate rewards.
    - Discount factor 0 means: agent will only learn the immediate reward
    - Discount factor 1 means: agent will learn till infinity
- 