# RL-Magic
## Introduction
Since playing hogwarts legacy I have been wondering how fezasible it would be to create a reinforcement learning wizard agent. Along with this sounding REALLY cool, I think it can atually be done.

## Phase 1: Complete Waves 1-5 of the wizarding arena
### Challenges
1. Define what the expected behavior is of agent wizard
    
      The expected behavior is for the wizard agent to destroy it's enemies in the shortest time possible and complete every wave. The wizard agent will be using spells, basic casts, and protego's stupendo to deal damage, and protego to protect itself.
3. Define a reward

      The reward for dealing damage will be scaled based on damage dealt. Time to complete a wave will also increase the reward given. Losing health or dying will result in -reward. 
5. Determine all of the actions that we want the agent to understand
6. Find a way to capture the state space
7. Filter the captured state space to real features
8. Use these features to determine what action should be taken

