
This repository contains labs for understanding and coding basic reinforcement learning concepts based on jupyter notebooks.

The labs are intended for being available to anyone through internet, so the assignments should be self-explanatory.

Most of the work was done by Yasmine Hamdani during a one month master internship

## Getting Started

### Download 

Get this repository using

```
git clone https://github.com/osigaud/rl_labs_notebooks.git
```

### Prerequisites

* Python 3.6
* Jupyter Notebook
* numpy
* matplotlib
* ipynb

### Installation

```
pip install -r requirements.txt

sudo updatedb

path1=$(locate new_ipynb_utils/utils.py)

path2=$(locate ipynb/utils.py)

cat "$path2" > "$path1"

```

Note : In order to enable the imports between notebooks, we used the [ipynb library](https://github.com/ipython/ipynb). 

The syntax to import a function, say sarsa() from the reinforcement_learning notebook, is as follows:

``` 
from ipynb.fs.defs.reinforcement_learning import sarsa
```

### Code


<br> 

There are 10 *.ipynb files to open on Jupyter Notebook.

* lab_instructions.ipynb : Summary of the lab. It contains the links to the different assignments, from Dynamic Programming to Reinforcement Learning algorithms. This is the file you will refer to when doing these labs.

* mdp.ipynb contains 4 classes :

		- maze : used to describe a maze like environment 
		
		- simple_actspace : used to describe an action space
		
		- mdp : generic class used to define a Markov Decision Process

		- maze_mdp : a class used to define a maze like Markov Decision Process

* maze_plotter.ipynb : used to show the states value functions and policies processed by the algorithms as well as the agent postion in RL algorithms.

* toolbox.ipynb : contains a few constants and functions used in most of the algorithms.
		

* the other notebooks are the different assignments of these labs, look at lab_instructions for more information.

### Running the labs

* open a terminal

* run "jupyter notebook"

* in your web browser, open "lab_instructions.ipynb"

* and follow instructions from there

### Contact

To contact me: Olivier.Sigaud@upmc.fr
