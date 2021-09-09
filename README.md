# Project 2: Continuous Control

## Project Details

This project trains a DDPG agent to move a double jointed arm to target locations. The state space has 33 continuous values and the action space has 4 continuous values representing torques for two joints.  

The task is episodic and is considered solved when an agent gets an average score of at least 30 over 100 consecutive episodes.

## Getting Started

Running the project requires the following python dependencies which can be installed with pip 

		Pillow>=4.2.1
		matplotlib
		numpy>=1.11.0
		jupyter
		pytest>=3.2.2
		docopt
		pyyaml
		protobuf==3.5.2
		grpcio
		torch
		pandas
		scipy
		ipykernel

It also requires the reacher environment, which can be dowloaded [here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Linux_NoVis.zip), unzip this file in the p2_continuous-control directory. 

Alternately, it can be run in the provided Udacity workspace, after installing dependencies with this command:

		pip -q install ./python

Continuous_Control.ipynb can be used to test the agent created for this project, by running the cells in order. To run in the Udacity workspace, the file name provided to the UnityEnvironment constructor must be changed to 

		/data/Reacher_Linux_NoVis/Reacher.x86_64
