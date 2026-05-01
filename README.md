# Self Paced Gaussian Reinforcement Learning

## Installation

It is easiest to setup a virtual or conda environment in order to isolate the packages installed for this project from your global python installation. 
```bash
pip install -r requirements.txt
```

This will install a wrapper for the MuJoCo simulation library. For this to work, you need to have set up MuJoCo according to [this guide](https://github.com/openai/mujoco-py).

## Quick Start


The experiments can be directly configured and excuted using the following commands
```python exp_point_mass3d_ppo.py 
python exp_lunar_lander_ppo.py 
python exp_ball_catching_ppo.py 
```


After running the experiments for the desired number of seeds, the results can be visualized using the following command
```python eval_point_mass3d_ppo.py 
python eval_lunar_lander_ppo.py 
python eval_ball_catching_ppo.py 
```

The Self-paced Deep Reinforcement Learning is also implemented as a baseline.
