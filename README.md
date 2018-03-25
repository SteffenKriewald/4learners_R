# SWC/DC workshops at Potsdam, Germany

This repository contains materials for [Software Carpentry](https://software-carpentry.org/) and [Data Carpentry](http://www.datacarpentry.org/) workshops hosted at Potsdam, Germany.

The present branch of the repository relates to the **R workshop -- An Introduction to Scientific Computing and Reproducible Research** held at [Potsdam Institute for Climate Impact Research (PIK)](https://www.pik-potsdam.de/), in Potsdam, Germany, on **25-26th of April 2018**.

The homepage with a detailed schedule for this particular workshop is found [here](https://swc-bb.github.io/2018-04-25-Potsdam-Berlin/).

The etherpad we used during the workshop if found [here](http://pad.software-carpentry.org/2018-04-25-Potsdam-Berlin).


If you want to get in touch with us, please email to swc-workshop-org@gfz-potsdam.de.

_If you are here because you are looking for a particular R workshop you attended in the past, make sure you visit the appropriate branch of this repository (note that the branches are ordered by date)._


***

The workshop focuses on three foundational tools for scientific computing and reproducible research:
* the shell
* git for version control
* scientific computing with R


## the shell

In this workshop we closely follow the Software Carpentry lesson [The Unix Shell](https://swcarpentry.github.io/shell-novice/).

## git for version control

In this workshop we closely follow the Software Carpentry lesson [Version Control with Git](https://swcarpentry.github.io/git-novice/).


## scientific computing with R

In this workshop we teach four main aspects of scientific computing with R.

* 01 - Introduction to R and Rstudio & Project Management
* 02 - Functions and Unittests
* 03 - Code Optimization, Profiling and Debugging
* 04 - Tidyverse for Data Analysis   
* 05 - Visualizations in R using `ggplot2`

All data sets and all code snippet for reproducibility are available through this self contained repository.

The structure of this repository is outlined below:

    4learners_R
    │.git                  # git internals
    │.gitignore            # specify files/folders to be ignored by git
    └───data
    │   │...               # find all the raw data files
    └───figures
    │   │...               # saved figures go here
    └───notebooks_and_scripts
    │   └───_img
    │   │   │...           # rendered images are placed here
    │   │...               # find all R scripts and notebooks for the workshop here
    │
    │README.md
    │
    └───src
        │...               # auxiliary code snippets and scripts
        └───_solutions
            │...           # solutions for coding challenges (don't cheat yourself ;-))


_Note that we are continuously developing our lessons, hence, come back once in a while and check the [master branch](https://github.com/swc-bb/4learners_R) for updates._


 ***
