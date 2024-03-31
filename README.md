# Enhancing Whale Acoustic Signal Analysis through Reinforcement Learning

**Authors:** Abdelhaleem SAAD, Worachit KETRUNGSRI, Yosef GUEVARA  
**Date:** February 9, 2023

## Introduction
The project explores the application of Reinforcement Learning (RL) to enhance the analysis of whale acoustic signals. Whales communicate via low-frequency sounds, which can be disrupted by anthropogenic noise. Using RL, we aim to de-noise these environmental sounds and identify whale calls more clearly.

## Whale Moaning Analysis
The study begins with understanding whale moaning characteristics and applying signal annotations to facilitate signal processing. This foundational work is crucial for distinguishing whale sounds from background noise in acoustic data.

![imagen](https://github.com/YosefGuevara012/Reinforcement_learning_for_underwater_acoustics/assets/54146941/62279fe0-16f4-4756-97ce-741cbc14db99)


## Signal Annotations and Processing
We manually annotate whale sounds using an audio editor and apply filters to highlight the desired signals. Our methodology includes several steps, such as low and high pass filtering, amplification, and visual inspection of signals.

![imagen](https://github.com/YosefGuevara012/Reinforcement_learning_for_underwater_acoustics/assets/54146941/c78a1512-5107-4694-8f5b-36786c5c5e3d)


## Signal Processing in Python
The signal processing script written in Python leverages energy detection and Continuous Wave transform (CWT) to map the signal frequency and identify whale moans within noisy recordings.

![imagen](https://github.com/YosefGuevara012/Reinforcement_learning_for_underwater_acoustics/assets/54146941/2abe1d75-1d03-494e-955d-3d545e022e62)


## Reinforcement Learning Agent and Environment
We implement an RL agent and define its environment, including observation and action spaces, a reward model, and the training procedure using Q-learning Algorithm and Epsilon-greedy policy.

![imagen](https://github.com/YosefGuevara012/Reinforcement_learning_for_underwater_acoustics/assets/54146941/2a1948d8-d381-48a4-8202-144a6cf8e2e0)


## Results and Conclusion
Our results demonstrate the RL agent's potential in identifying the optimal frequency range for detecting whale vocalizations, despite challenges in achieving consistent performance. The adaptability of the agent's decision-making framework is crucial for accurate identification of whale calls.

![imagen](https://github.com/YosefGuevara012/Reinforcement_learning_for_underwater_acoustics/assets/54146941/cb1fbc9f-55e4-4360-8a1a-660404d6e882)


