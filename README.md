
**Dynamic Maze Routing with Deep Reinforcement Learning**

This project implements a dynamic routing system for connecting pins in a maze environment using a combination of the A* algorithm and Deep Q-Learning (DQN). The agent dynamically selects which pin to route based on the shortest path and adjusts its strategy as paths become blocked. The goal is to optimize routing decisions while adapting to changes in the environment.

**Features--**
**1.A Algorithm for Shortest Path:** Efficient pathfinding between start and goal points in the maze.

**2.Dynamic Route Blockages:** Paths taken for one pin become blockages for subsequent pins.

**3.Deep Q-Learning:** Reinforcement learning to train an agent for optimal pin selection.

**4.Environment Visualization:** Visual representation of the maze and routing paths.

**5.Replay Buffer for Training:** Improves the agent's learning efficiency by sampling past experiences.


**Key Components--**

**A_star Algorithm-**

Efficiently calculates the shortest path while considering dynamic blockages.

**DQN (Deep Q-Network)-**

The DQN consists of a neural network that approximates Q-values for actions (selecting pins) given the current maze state.

**Reward System-**

Successful routing: +1 - 0.01 * len(path)

Failed routing: -0.1

**Contributions--**

Contributions are welcome! Please open an issue or submit a pull request for any improvements or new features.

