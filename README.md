
# Project 1: Navigation

### Project Environment Details

In this project, an agent navigates a large, square world to collect yellow bananas and avoid blue bananas.  

A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana.  Thus, the goal of your agent is to collect as many yellow bananas as possible while avoiding blue bananas.  

The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around agent's forward direction.  Given this information, the agent has to learn how to best select actions.  Four discrete actions are available, corresponding to:
- **`0`** - move forward.
- **`1`** - move backward.
- **`2`** - turn left.
- **`3`** - turn right.

The task is episodic, and in order to solve the environment, your agent must get an average score of +13 over 100 consecutive episodes.

### Installing Dependencies

1. Create a virtual Python environment (3.6 version is very important!):
(conda create --name drlnd python=3.6)

2. Activate the virtual Python environment: 
(for Unix: source activate drlnd)
(for Windows: activate drlnd)

3. Install gym 
(pip install gym)

4. Clone the repository https://github.com/kimkevin711/drlp1_navigation.git:
(git clone https://github.com/kimkevin711/drlp1_navigation.git)

5. Go to Folder and install other modules:
(cd drlp1_navigation/python)
(pip install .)

6. Create IPython kernel for drlnd environment:
(python -m ipykernel install --user --name drlnd --display-name "drlnd")

7. Download the environment from one of the links below.  You need only select the environment that matches your operating system:
    - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
    - Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)
    - Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)
    - Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)
    
    (_For Windows users_) Check out [this link](https://support.microsoft.com/en-us/help/827218/how-to-determine-whether-a-computer-is-running-a-32-bit-version-or-64) if you need help with determining if your computer is running a 32-bit version or 64-bit version of the Windows operating system.

    (_For AWS_) If you'd like to train the agent on AWS (and have not [enabled a virtual screen](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Training-on-Amazon-Web-Service.md)), then please use [this link](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux_NoVis.zip) to obtain the environment.

8. Place the file in the GitHub repository you just cloned, in the `p1_navigation/` folder, and unzip (or decompress) the file (if necessary). 

### Instructions 

1. Open the `Navigation.ipynb` notebook in the p1_navigation folder.

2. Run all cells in Section 1 (import modules, start environment, and see environment brain name).

3. Run all cells in Section 2 (examine state and action spaces).

4. Run all cells in Section 5 (import best saved weights and test agent).



