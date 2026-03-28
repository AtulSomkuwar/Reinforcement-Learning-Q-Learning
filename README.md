# Reinforcement-Learning / Q-Learning

Steps are involved
1) Creating Enviornment class setting up grid size, starting position, end position and various obstacle locations based on the co-ordinates also declared the max      reward as 10 and max penalty as -10
2) Agent moves in a environment learning rate = 0.9, gamma = 0.95, eps = 1.0
3) Q(s,a) = r + γ max Q(s',a') # Bellman Equation
4) Training with episodes = 1000, max-steps = 200 for every episodes we will receive rewards
5) ## Result 
6) <img width="409" height="99" alt="Screenshot 2026-03-29 000319" src="https://github.com/user-attachments/assets/ecddf1c9-cb12-4cad-927e-d5775d744c63" />
7) ## Rewards Vs Episodes
8) <img width="784" height="625" alt="Screenshot 2026-03-29 000335" src="https://github.com/user-attachments/assets/434c91f1-bd4d-4535-b7a4-1c9da8fbccbd" />
## Original Grid Architecture
<img width="569" height="595" alt="Screenshot 2026-03-28 234943" src="https://github.com/user-attachments/assets/3b111817-db35-44e7-a815-77d77c723805" />

## Agest Finds Optimal Path
<img width="573" height="591" alt="Screenshot 2026-03-28 235017" src="https://github.com/user-attachments/assets/e6d92644-fa1d-45ba-b0c1-e5ed210a3ee8" />

## Agent Reaches to the Goal (Giff)
![gridworld_path](https://github.com/user-attachments/assets/2ea9392e-4299-4b15-b6cd-87a772da9397)

