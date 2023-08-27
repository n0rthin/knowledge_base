Setup:
Goal
Possible actions
Initial beliefs
States

Loop:
1. Observe
2. If there is an expected outcome: given observations, action, and expected outcome update beliefs
3. Given observations, goal, possible actions, and beliefs generate next action that will most likely brings agent closer to goal
4. Given next action, observations, and beliefs generate expected outcome
5. Do action
6. Go to 1


Loop without learning:
1. Observe
2. Infer hidden states
3. Infer action
4. Do action
5. Go to 1