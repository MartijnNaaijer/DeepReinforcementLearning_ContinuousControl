# Continuous Control

![alt text](https://video.udacity-data.com/topher/2018/June/5b1ea778_reacher/reacher.gif "Follow me!")

In this repository a continuous control problem is solved using deep reinforcement learning, more specifically with Deep Deterministic Policy Gradient. The environment which is used here is Unity's Reacher. In this environment, a double jointed arm needs to reach moving target locations. 

The environment has two versions:
*The first version contains a single agent.
*The second version contains 20 identical agents, each with its own copy of the environment.

In this repository only the second version is considered. 

On every time step that the hand is in the target location, the agent gets a reward of +0.1. The goal is to remain in the target location as long as possible.

The observation space consists of 33 variables corresponding to position, rotation, velocity, and angular velocities of the arm. Each action is a vector with four numbers, corresponding to torque applicable to two joints. Every entry in the action vector should be a number between -1 and 1.

After each episode, the rewards of the 20 agents are averaged. The environment is solved if the average score is at least +30 over 100 subsequent episodes.

If you want to run the file reacher_continuous_control.ipynb on your own computer install Anaconda (Python3), then download this repository and install the unity environment. You can download it here:

[Linux](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher_Linux.zip)

[MacOS](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher.app.zip)

[Windows32bit](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher_Windows_x86.zip)

[Windows 64 bit](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher_Windows_x86_64.zip)

Then, place the file in the p2_continuous-control/ folder in the DRLND GitHub (https://github.com/udacity/deep-reinforcement-learning) repository, and unzip (or decompress) the file.

Finally, run the notebook reacher_continuous_control.ipynb.

