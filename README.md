## GYM-WEBOTS [WIP]
### The project is currently incomplete. Will resume work on this when I have more time.

### Available environments
- `wb-4wheels-v0`: Webots 4 Wheel robot with 2 distance sensors.

### Installation

- pip install gym
- pip install -e . (inside repo folder)

Then run:
```
import gym
import gym_webots
env = gym.make('wb-4wheels-v0')
```
