# Predicting-Bike-Sharing-Data

The predicting bike sharing data project by Udacity inc. takes in bike sharing data and an basic neural network python class, design by me, and outputs bike sharing data analytics. This project repo is for educational purpose and should be used as a tool, not for copying. If viewing or using this repo, please follow the Udacity Honor Code and Community Code of Conduct: https://www.udacity.com/legal/community-guidelines

This neural network is used to predict bike usage and city events corresponding to years 2011 and 2012 from Capital Bikeshare system, Washington D.C., USA which is publicly available in http://capitalbikeshare.com/system-data. 

All data analytics can be previewed at Your_first_neural_network.html which is an output of the jupyter notebook Your_first_neural_network.ipynb. 




---

# Run (dependencies are required to run)

To run turn on the `predicting-bike-sharing-data` environment as defined in dependenceies 


```
git clone https://github.com/jujbates/Predicting-Bike-Sharing-Data.git
cd Predicting-Bike-Sharing-Data
jupyter notebook

```

You can open the file `Your_first_neural_network.ipynb` in the browser with the jupyter notebook, and run all cells. This will give you the same output find in the `Your_first_neural_network.html` file. But if you could to walk there the `Your_first_neural_network.ipynb` file and run it cell by cell these are the step that you would be taking. 
0. import libraries
1. Load and prepare the data
2. Checking out the data
    - Dummy variables
    - Scaling target variables
    - Splitting the data into training, testing, and validation sets
3. Time to build the network (The Neural Network I design is found in my_answer.py in a class called NeuralNetwork)
4. Unit tests
5. Training the network
    - Choose the number of iterations
    - Choose the learning rate
    - Choose the number of hidden nodes
6. Check out your predictions
7. Thinking about your results(this question will not be evaluated in the rubric).
    - How well does the model predict the data? 
    - Where does it fail? 
    - Why does it fail where it does?

---

# Dependencies

## Configure and Manage Your Environment with Anaconda

Per the Anaconda [docs](http://conda.pydata.org/docs):

> Conda is an open source package management system and environment management system 
for installing multiple versions of software packages and their dependencies and 
switching easily between them. It works on Linux, OS X and Windows, and was created 
for Python programs but can package and distribute any software.


## Overview
Using Anaconda consists of the following:

1. Install [`miniconda`](http://conda.pydata.org/miniconda.html) on your computer, by selecting the latest Python version for your operating system. If you already have `conda` or `miniconda` installed, you should be able to skip this step and move on to step 2.
2. Create and activate * a new `conda` [environment](http://conda.pydata.org/docs/using/envs.html).

\* Each time you wish to work on any exercises, activate your `conda` environment!

---

## 1. Installation

**Download** the latest version of `miniconda` that matches your system.

|        | Linux | Mac | Windows | 
|--------|-------|-----|---------|
| 64-bit | [64-bit (bash installer)][lin64] | [64-bit (bash installer)][mac64] | [64-bit (exe installer)][win64]
| 32-bit | [32-bit (bash installer)][lin32] |  | [32-bit (exe installer)][win32]

[win64]: https://repo.continuum.io/miniconda/Miniconda3-latest-Windows-x86_64.exe
[win32]: https://repo.continuum.io/miniconda/Miniconda3-latest-Windows-x86.exe
[mac64]: https://repo.continuum.io/miniconda/Miniconda3-latest-MacOSX-x86_64.sh
[lin64]: https://repo.continuum.io/miniconda/Miniconda3-latest-Linux-x86_64.sh
[lin32]: https://repo.continuum.io/miniconda/Miniconda3-latest-Linux-x86.sh

**Install** [miniconda](http://conda.pydata.org/miniconda.html) on your machine. Detailed instructions:

- **Linux:** http://conda.pydata.org/docs/install/quick.html#linux-miniconda-install
- **Mac:** http://conda.pydata.org/docs/install/quick.html#os-x-miniconda-install
- **Windows:** http://conda.pydata.org/docs/install/quick.html#windows-miniconda-install


## 2. Create and Activate the Environment

For Windows users, these following commands need to be executed from the **Anaconda prompt** as opposed to a Windows terminal window. For Mac, a normal terminal window will work. 

#### Git and version control
These instructions also assume you have `git` installed for working with Github from a terminal window, but if you do not, you can download that first with the command:
```
conda install git
```

**Now, we're ready to create our local environment!**

1. Clone the repository, and navigate to the downloaded folder. This may take a minute or two to clone due to the included image data.
```
git clone https://github.com/jujbates/Predicting-Bike-Sharing-Data.git
cd Predicting-Bike-Sharing-Data
```

2. Create (and activate) a new environment, named `predicting-bike-sharing-data` with Python 3.6. If prompted to proceed with the install `(Proceed [y]/n)` type y.

	- __Linux__ or __Mac__: 
	```
	conda create -n predicting-bike-sharing-data python=3.6
	source activate predicting-bike-sharing-data
	```
	- __Windows__: 
	```
	conda create --name predicting-bike-sharing-data python=3.6
	activate predicting-bike-sharing-data
	```
	
	At this point your command line should look something like: `(predicting-bike-sharing-data) <User>:predicting-bike-sharing-data <user>$`. The `(predicting-bike-sharing-data)` indicates that your environment has been activated, and you can proceed with further package installations.



3. Install a few required pip packages, which are specified in the requirements text file (including OpenCV).
```
pip install -r requirements.txt
```

7. That's it!

Now most of the `predicting-bike-sharing-data` libraries are available to you. Very occasionally, you will see a repository with an addition requirements file, which exists should you want to use TensorFlow and Keras, for example. In this case, you're encouraged to install another library to your existing environment, or create a new environment for a specific project. 


---

## Installing Jupyter with pip
As an existing or experienced Python user, you may wish to install Jupyter using Python’s package manager, pip, instead of Anaconda.

If you have Python 3 installed (which is recommended):

`python3 -m pip install --upgrade pip`

`python3 -m pip install jupyter`

If you have Python 2 installed:

`python -m pip install --upgrade pip`

`python -m pip install jupyter`

Congratulations, you have installed Jupyter Notebook! To run the notebook, run the following command at the Terminal (Mac/Linux) or Command Prompt (Windows):

`jupyter notebook`


Now, assuming your `predicting-bike-sharing-data` environment is still activated, you can navigate to the main repo and start looking at the notebooks:


```
cd
cd predicting-bike-sharing-data
jupyter notebook
```

To exit the environment when you have completed your work session, simply close the terminal window.