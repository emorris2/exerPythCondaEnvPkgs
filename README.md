# Setting up Environments and Installing Packages Using Conda

## Summary of steps to complete

- [ ] Fork this repository so you have your own copy to work on.
- [ ] Clone the repository on your local machine. 
- [ ] Edit this README.md file on your machine.
- [ ] Run the Conda commands shown in the video and describe them in the table below.
- [ ] Push your changes to your GitHub repository.
- [ ] Submit a link to this GitHub repository in Canvas.

## 1. Fork & Clone this repository

* We did this in a previous assignment. Instructions are here: https://github.com/cmcntsh/N6806_Fall2020_DevNotes/blob/master/Projects/002%20-%20Practice%20Using%20Git%20and%20GitHub/README.md
* This can also be done directly in VSCode
  * Create a new folder on your machine where you want to put this repository if you don't already have one you want to use.
  * Copy the Clone or Download path for this repository from GitHub.
  * In VSCode from the command pallette (Ctrl-Shift-P) run Git: Clone
  * Paste the path into the path field which pops up
  * Select your new folder you created on your machine
  * A new folder for the repository with the repository files should be in the folder you selected showing in the Explorer window in VSCode on the left side.
  
## Edit your README.md file

* [ ] In an editor of your choice (i.e. VSCode) edit this README.md file to add the answers requested in the tables.

## Follow along with this tutorial

* Conda What and Why? (27 min): https://www.youtube.com/watch?v=23aQdrS58e0&list=PLG9A6ovzPqX6d9uWzx0UYN9pm0zzl5ofA&index=13&t=0s
  * He installs Miniconda. We will be using Anaconda. Don't install Miniconda.
  * Follow along with the rest of the tutorial.
  * Go ahead and create the environments as he creates them in the tutorial.

## Conda Concepts
Make changes for assignment

* [ ] Describe the Conda concepts used in the video and listed in the table below.

|   Concept   |         Description or short answer         |
|     ---     |                     ---                     |
|What is the purpose of having different environments?     |(To manage different packages that are needed for different projects.)|
|What is the default package manager in Python?            |(Pip)|
|How do you manage environments and packages in Anaconda?  |(Install Conda on computer and use it.)|
|`conda list`       |(List shows default packages installed on computer)|
|`conda env list`       |(List of default environments installed.)|
|How do you keep your base environment unchanged?       |(Make a separate new environment different from base.)|
|What is the link to the Conda cheat sheet? (link in video notes is broken)      |(https://conda.io/projects/conda/en/latest/user-guide/cheatsheet.html)|
|`conda create --name XXXX`       |(conda create --name ai383 python=3.8.3 created new environment to work in.)|
|`source activate XXXX`       |(Conda activate ai383 run It, it shows you are working in new environment)|
|`conda install YYYY`       |(Conda install Numpy installed numpy in da35 soenvironment)|
|channels in Conda       |(describes path where conda looks for packages available.)|
|`conda install -c ZZZZ YYYY`       |(Use channel one time to get package)|
|`conda config --show channels`       |(default channel-path conda uses when conda install runs to find packages)|
|`conda config --add channels ZZZZ`       |(able to add to channel and keep on channel list)|
|conda-forge.org       |(different channel for python but community led.)|
|`source deactivate`       |(takes you to base channel.)|
|`conda config --get channels`       |(Shows channels in low to high priority where conda will look.)|

* After creating the environments he created in the video on your computer, what would the results of running the command `conda env list` look like with the da35 environment activated. Paste the output from your command prompt in the code block below.

```
#Paste your results here.

(da35) C:\Users\emaem>conda env list
# conda environments:
#
base				C:\Users\emaem\anaconda3
ai383				C:\Users\emaem\anaconda3\envs\ai383
da35			    * C:\Useers\emaem\anaconda3\envs\da35

```
* What command would you use to remove the environments you created for this exercise from your computer?

```
#Type the command here.

Conda env remove –-name bio-env


End of assignment.
End of assignment that is due 9/8/20.
```
