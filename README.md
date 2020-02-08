## The Environment

For this project, you will work with the Tennis environment.

![Tennis](tennis.png)

In this environment, two agents control rackets to bounce a ball over a net. If an agent hits the ball over the net, it receives a reward of +0.1. If an agent lets a ball hit the ground or hits the ball out of bounds, it receives a reward of -0.01. Thus, the goal of each agent is to keep the ball in play.

The observation space consists of 8 variables corresponding to the position and velocity of the ball and racket. Each agent receives its own, local observation. Two continuous actions are available, corresponding to movement toward (or away from) the net, and jumping.

The task is episodic, and in order to solve the environment, your agents must get an average score of +0.5 (over 100 consecutive episodes, after taking the maximum over both agents). Specifically,

    After each episode, we add up the rewards that each agent received (without discounting), to get a score for each agent. This yields 2 (potentially different) scores. We then take the maximum of these 2 scores.
    This yields a single score for each episode.

The environment is considered solved, when the average (over 100 episodes) of those scores is at least +0.5.

Follow the instructions below to explore the environment on your own machine! You will also learn how to use the Python API to control your agent.

### Step 1: Activate the Environment

If you haven't already, please follow the instructions in the DRLND GitHub repository to set up your Python environment. These instructions can be found in README.md at the root of the repository. By following these instructions, you will install PyTorch, the ML-Agents toolkit, and a few more Python packages required to complete the project.

(For Windows users) The ML-Agents toolkit supports Windows 10. While it might be possible to run the ML-Agents toolkit using other versions of Windows, it has not been tested on other versions. Furthermore, the ML-Agents toolkit has not been tested on a Windows VM such as Bootcamp or Parallels.

    SPECIAL NOTE TO BETA TESTERS - please also download the p3_collab-compet folder from here and place it in the DRLND GitHub repository.

### Step 2: Download the Unity Environment

For this project, you will not need to install Unity - this is because we have already built the environment for you, and you can download it from one of the links below. You need only select the environment that matches your operating system:

    Linux: click here
    Mac OSX: click here
    Windows (32-bit): click here
    Windows (64-bit): click here

Then, place the file in the p3_collab-compet/ folder in the DRLND GitHub repository, and unzip (or decompress) the file.

(For Windows users) Check out this link if you need help with determining if your computer is running a 32-bit version or 64-bit version of the Windows operating system.

(For AWS) If you'd like to train the agent on AWS (and have not enabled a virtual screen), then please use this link to obtain the "headless" version of the environment. You will not be able to watch the agent without enabling a virtual screen, but you will be able to train the agent. (To watch the agent, you should follow the instructions to enable a virtual screen, and then download the environment for the Linux operating system above.)

### Step 3: Explore the Environment

After you have followed the instructions above, open Tennis.ipynb (located in the p3_collab-compet/ folder in the DRLND GitHub repository) and follow the instructions to learn how to use the Python API to control the agent.

Watch the (silent) video below to see what kind of output to expect from the notebook, if everything is working properly!

In the last code cell of the notebook, you'll learn how to design and observe an agent that always selects random actions at each timestep. Your goal in this project is to create an agent that performs much better!

## Project Instructions

For this project, you will train an agent to solve the provided environment.

To submit the project, you will provide a link to a GitHub repository with your implementation. If you would like a refresher on GitHub, please check out the lessons on GitHub in the extracurricular content.

To review the detailed project requirements, please read the project rubric.

The format of this project is largely open-ended; you need only satisfy the points in the rubric. For instance, while we suspect that the majority of students will train the agent in a Jupyter notebook, you are welcome to instead structure your repository so that your Python code is run from the command line instead.
Your GitHub Submission

As described in the rubric, your GitHub submission should contain:

    a README that describes how someone not familiar with this project should use your repository. The README should be designed for a general audience that may not be familiar with the Nanodegree program; you should describe the environment that you solved, along with how to install the requirements before running the code in your repository.
    the code that you use for training the agent, along with the trained model weights.
    a report describing your learning algorithm. This is where you will describe the details of your implementation, along with ideas for future work.

This GitHub repository will serve as a portfolio piece to share your new skills with the global community of reinforcement learning students and practitioners, along with potential employers!
Project Workspace

While you are welcome to train the agent locally on your own machine, you can also complete the project in the Workspace that appears towards the end of this lesson. Note that the Workspace does not allow you to see the simulator of the environment; so, if you want to watch the agent while it is training, you should train locally.

The Workspace provides a Jupyter server directly in your browser and has GPU support. You can learn more about the Workspace by perusing the Udacity Workspaces lesson in the extracurricular content.

