# Trading-Bot-Reinforcement-Learning
Trading bot created using stable baselines3. 
This repo contains:
1. [Apple marketwatch](https://www.marketwatch.com) data from 12 August 2021 to 12 August 2022. 
2. Model logs
3. Saved Models
4. ipynb of training the model. 
5. ipynb of loading the model. 

Agent is expected to learn useful action sequences to maximize profit in a given environment.
Environment limits agent to either buy or sell at each step.

Only a single position can be opened per trade.

The project makes use of [stable baselines3](https://stable-baselines3.readthedocs.io/en/master/) api for deploying the algorithms. I have also used [FinTA](https://github.com/peerchemist/finta) for calculating the technical indicators. I have also used [gym-anytrading](https://github.com/AminHP/gym-anytrading) environment to train my agent. 

The bot in the end was able to earn a decent profit of 6.24% over a period of 60 days at it's best. The project hence was able to demonstrate power of Reinforcement Learning in finance. 
