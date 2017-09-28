# ml-helloworld-with-tensorflow-keras
Code and Slides for 'Hello World: An  Intro to Machine Learning with TensorFlow and Keras'


## Brief Description

With all the hype right now around Machine Learning and AI, it's easy to become confused on how and where to get started. Do you focus on the math, or the frameworks, or the problems? I will teach you what Machine Learning is (and what it's not) and how to get started with TensorFlow/Keras. Attendees will leave having seen a practical example of how to predict handwritten numbers and the knowledge that Machine Learning is approachable and fun.

You can follow along with the slides at 

 - [Slidedeck](https://docs.google.com/presentation/d/1gTPX4vpLJAT10m2sOMZOwFxPNYQrtXPRpJntnS_SBX8/edit?usp=sharing)


Here are the tools we're going to use:

  - Python
  - Anaconda
  - Jupyter Notebook
  - Pandas
  - TensorFlow
  - Iris Dataset
  - Keras
 

## Setup
### Step 1: Clone the [ml-helloworld-with-tensorflow-keras](https://github.com/weklund/ml-helloworld-with-tensorflow-keras/) repository

- You can should be able to use any Linux, Mac OS X, or Windows computer with a web browser for this tutorial.  I recommend using Chrome, but the code should also work in Firefox and Safari.
- Clone this repository, e.g. using `git clone https://github.com/weklund/sentiment-analysis`.
- Open a terminal window inside the repository.

Please *do a `git pull`* on this cloned repository 

### Step 2: Create a conda environment from `env.yml`

The easiest way to get an environment set up for the tutorial is installing it using the `environment.yml` provided. If you do not already have it, install [`conda`](https://www.continuum.io/downloads), and then create the `bk_tutorial` environment by executing:
```
conda env create -f env.yml
```

When installation is complete you may activate the environment by running the command:
```
activate ml-keras-flask-helloworld
```
(for Windows) or:
```
$ source activate ml-keras-flask-helloworld
```
(for Linux and Mac).

Later, when you are ready to exit the environment after the tutorial, you can type:
```
deactivate
```
(for Windows) or:
```
$ source deativate
```
(for Linux and Mac).

If for some reason you want to remove the environment entirely, you can do so by writing:
```
conda env remove --name ml-keras-flask-helloworld
```

For additional information about working with `conda` environments, consult the [`conda` documentation](https://conda.io/docs/using/envs.html#managing-environments).

### Step 3: Launch Jupyter Notebook
After cloning the repository then setting up and activating the virtual environment, you can launch the notebook server and client by executing:
```
(ml-keras-flask-helloworld)$ jupyter notebook --NotebookApp.iopub_data_rate_limit=100000000
```

A browser window with a Jupyter Notebook instance should now open, letting
you select and execute each notebook. (Increasing the rate limit in
this way is required for the current 5.0 Jupyter version, but should
not be needed in earlier or later Jupyter releases.)


Step 5: Test that everything is working
---------------------------------------

You can see if everything has installed correctly by selecting the
`ml-keras-flask-helloworld.ipynb` notebook and doing "Cell/Run All" in the menus.
There may be warnings on some platforms, but you'll know it is working
if you see an output after each cell.



## Additional Resources
### Documentation
  - [Anaconda Install](https://docs.anaconda.com/anaconda/install/)
  - [Jupyter Documentation](https://jupyter.readthedocs.io/en/latest/)
  - [Pandas Documentation](http://pandas.pydata.org/)
  - [TensorFlow Documentation](https://www.tensorflow.org/get_started/)

### Get Involved - **Contributions Welcome!**
  - [Pandas repo](https://github.com/pandas-dev/pandas)
  - [TensorFlow repo](https://github.com/tensorflow/tensorflow)

