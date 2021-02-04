# 🚀 Deep Reinforcement Learning Nanodegree ![udacity](https://img.shields.io/badge/-Udacity-02B3E4?style=flat-square&logo=Udacity&logoColor=white)

This [nanodegree program](https://www.udacity.com/course/deep-reinforcement-learning-nanodegree--nd893) by Udacity consits of 4 courses - **Foundations of Reinforcement Learning**, **Value-Based Methods**, **Policy-Based Methods**, **Multi-Agent Reinforcement Learning** -  to learn cutting-edge deep reinforcement learning algorithms from Deep Q-Networks (DQN) to Deep Deterministic Policy Gradients (DDPG) and apply these concepts to train agents to walk, drive, or perform other complex tasks.

The 3 projects I completed as part of this nanodegree:
- [Navigation Project](https://github.com/XandraV/deep-reinforcement-learning-nanodegree/tree/master/navigation) :octocat:

- [Continuous Control Project](https://github.com/XandraV/deep-reinforcement-learning-nanodegree/tree/master/continuous-control) :octocat:

- [Collaboration and Competition Project](https://github.com/XandraV/deep-reinforcement-learning-nanodegree/tree/master/collab-compet) :octocat:

## Getting Started 

First clone this repository. To set up your python environment, follow the instructions below.

1. Create (and activate) a new environment with Python 3.6.  
```bash
python -m ipykernel install --user --name drlnd --display-name "drlnd"
conda create --name drlnd python=3.6 
activate drlnd
```
	
    
2. Follow the instructions in [this repository](https://github.com/openai/gym) to perform a minimal install of OpenAI gym.
	- Next, install the **classic control** environment group by following the instructions [here](https://github.com/openai/gym#classic-control).
	- Then, install the **box2d** environment group by following the instructions [here](https://github.com/openai/gym#box2d).
	```bash
	pip install gym
	```
	
    
3. Install several dependencies
```bash
conda install Pillow matplotlib numpy jupyter pytest docopt pyyaml protobuf grpcio pandas scipy ipykernel
conda install -y pytorch -c pytorch
pip install tensorflow==2.2.0rc4
pip install unityagents
```

4. Download the environment from one of the links below.  You need only select the environment that matches your operating system:
    
    ### Project 1: Navigation
    
    ![image1](https://user-images.githubusercontent.com/10624937/42135619-d90f2f28-7d12-11e8-8823-82b970a54d7e.gif)
    - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
    - Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)
    - Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)
    - Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)
    
   ###  Project 2: Continuous Control: [Reacher](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Learning-Environment-Examples.md#reacher) environment.
    
    ![image1](https://user-images.githubusercontent.com/10624937/43851024-320ba930-9aff-11e8-8493-ee547c6af349.gif)
    - **_One (1) Agent_**
        - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Linux.zip)
        - Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher.app.zip)
        - Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Windows_x86.zip)
        - Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Windows_x86_64.zip)

    ### Project 3: Collaboration and Competition [Tennis](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Learning-Environment-Examples.md#tennis) environment.
    
    ![gif](https://user-images.githubusercontent.com/10624937/42135623-e770e354-7d12-11e8-998d-29fc74429ca2.gif)
    - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Linux.zip)
    - Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis.app.zip)
    - Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Windows_x86.zip)
    - Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Windows_x86_64.zip)
    
5. Place the environment file in the corresponding project folder `navigation/` or `continuous-control/` or `collab-compet/` and unzip (or decompress) the file. 

6. Follow the instructions in `Navigation.ipynb` / `Continuous_Control.ipynb` / `Tennis.ipynb` to get started with training your own agent!  
