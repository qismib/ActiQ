# ActiQ: Quantum and Classical Reinforcement Learning

## Overview
Learning from experience is essential for tackling complex challenges, recognizing patterns, and making informed decisions. This project explores **Reinforcement Learning (RL)**, a method of learning based on optimizing actions through rewards, integrating quantum computing to evaluate its potential compared to classical methods.

The project compares:
- **Deep Q-Learning (DQN)**: A classical neural network used to estimate state-action values.
- **Parameterized Quantum Circuits (PQC)**: A hybrid classical-quantum approach, simulated using parametrized quantum circuits to enhance learning capability.

## Methods
Experiments were conducted using Python with TensorFlow and TensorFlow Quantum, and tested in the **Acrobot-v1** environment from OpenAI Gym, where the agent controls a robotic arm to reach a predefined height, with penalties for each failed action.

Three key parameters were varied:
1. **Batch Size**: Number of episodes sampled during training.
2. **Model Architecture**: Number of neurons in hidden layers (classical) or variational layers (quantum).
3. **Learning Rate**: Speed at which parameters are updated.

## Results
- The quantum approach learns faster initially, reaching a reward of **-140** in 600 episodes, but is limited by the computational cost of quantum simulation.
- The classical model, trained over 20,000 episodes, reaches an optimal reward of **-70** with a more stable policy.
- **Conclusion**: Classical methods remain more effective for practical applications, but quantum computing shows promising future potential.

## Future Work
Future research will include testing on real quantum hardware (e.g., IBM Quantum) to assess performance in real-world conditions, improving both algorithms and hardware.

---

This project represents a step toward integrating classical learning with quantum technologies for tackling complex challenges in reinforcement learning.
