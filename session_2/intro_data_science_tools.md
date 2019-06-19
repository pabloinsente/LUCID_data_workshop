
# Outline

## I. Introduction
- Data Science workflow
- Data Science tools
- Data Science development environment

## II. Setting up Data Science tools and environment

### Terminal emulator  
- For MacOS users  
https://www.iterm2.com/  
- For Linux users
https://gnunn1.github.io/tilix-web/
- For Windows users
https://git-scm.com/downloads

### ATOM text editor
- Install  https://atom.io/
- Install teleptype package
- Install jedi package
- Install a Theme :)

### Python with Anaconda

- Follow instructions for your OS https://docs.anaconda.com/anaconda/install/
- Test installation. In the terminal type:  ```conda --version```  
- Set up a virtual environment with conda. In the terminal type (replacing 'myenv' with your environment name): ``` conda create --name myenv```
- Activate environment. In the terminal type:```conda activate myenv```
- Check your environment. In the terminal type:```conda info --envs```
- More info about managing virtual environments at https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html

### Jupyter notebooks/lab   

- Install jupyter lab in your new virtual environment. In the terminal type:```conda install -c conda-forge jupyterlab```
- Test installation. In the terminak type:```conda list | grep jupyter```
- More info about jupyter lab at: https://jupyterlab.readthedocs.io/en/stable/getting_started/installation.html
- Run jupyter lab. In the terminal type:```jupyter lab```
- Let's play with jupyter for a bit...
- Install package in the virtual environment

### IRKernel (to run R on Jupyter)
- Install IRKernel to run R in jupyter lab in your virtual environment. Google: ```anaconda irkernel``` and follow instructions
- Open a new terminal, activate environment, and run jupyter lab
- Let's play with the Rkernel a bit...

### Git and GitHub
- Install git https://git-scm.com/
- Create a GitHub account at GitHub
- what is GitHub? https://www.youtube.com/watch?v=w3jLJU7DT5E
- ***GitHub basics***:  
  - **Create** a GitHub Repository online
  - **Clone** your new Repository into a local directory. In the terminal type:```git clone url-git-repo```
  - Add our new jupyter script to your Repository locally
  - Edit your **README.md** file in ATOM
  - **Add** your changes to git. In the terminal type:```git add -A```
  - **Commit** your changes to git. In the terminal type:```git commit -m "first commit"```
  - Check that your branch is clean. Type in the terminal:```git status```
  - **Create a branch**. In the Terminal type:```git branch new-branch``` and then ```git checkout new-branch```
  - Let's edit some files in your new-branch
  - Repeat add, commit, and push to your new-branch
  - Change back to your master-branch. Type in the terminal:```git checkout master```
  - **Merge** your branches. Type in the terminal:```git merge new-branch```

### Google Colab (If time..)
- Go to https://colab.research.google.com


## Resources to learn:
### Bash/Shell
- https://www.codecademy.com/learn/learn-the-command-line/modules/bash-scripting
- https://linuxacademy.com/linux/training/course/name/the-system-administrators-guidep-to-bash-scripting

### Python
- https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-0001-introduction-to-computer-science-and-programming-in-python-fall-2016/
- https://www.codecademy.com/learn/learn-python-3
- https://www.coursera.org/learn/python-data-analysis

### R
- https://www.coursera.org/learn/r-programming
- https://r4ds.had.co.nz/

### Git/GitHub
- https://www.codecademy.com/learn/learn-git
