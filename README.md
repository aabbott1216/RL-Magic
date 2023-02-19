# RL-Magic
## Introduction
Since playing hogwarts legacy I have been wondering how fezasible it would be to create a reinforcement learning wizard agent. Along with this sounding REALLY cool, I think it can atually be done.

## Phase 1: Complete Waves 1-5 of the wizarding arena
### Challenges
1. Define what the expected behavior is of agent wizard
    
      The expected behavior is for the wizard agent to destroy it's enemies in the shortest time possible and complete every wave. The wizard agent will be using spells, basic casts, and protego's stupendo to deal damage, and protego to protect itself.
2. Define a reward

      The positive reward will be: 
      1. Dealing damage (scaled on damage dealt)
      2. Un-Aliving enemies (flat for ever enemy unalived)
      3. Time to complete a wave (Scaled, lower is better)
      4. successful protegos/perfect protegos/dodges (Reward more for perfect protegos)
       
      The negative rewards will be:
      1. Losing health (scaled with amount lost)
      2. Unaliving (big loss)

3. Determine all of the actions that we want the agent to understand
      The actions are as follows:
      1. Move camera right (right swipe)
      2. Move camera left (left swipe)
      3. Move forward (w)
      4. Protego+stupendo (hold q)
      5. dodge (tab)
      6. Spell 1 (1)
      7. Spell 2 (2)
      8. Spell 3 (3)
      9. Spell 4 (4)
5. Find a way to capture the state space
6. Filter the captured state space to real features
7. Use these features to determine what action should be taken

