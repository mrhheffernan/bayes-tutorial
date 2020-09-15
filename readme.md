# Bayesian tutorial journal clubs

These introductory sessions are resources for tutorials in the McGill Nuclear Theory group by Matthew Heffernan and are lightly, if at all, modified from Dick Furnstahl's excellent course at The Ohio State University. See [my fork of his course repository](https://github.com/mrhheffernan/Physics-8805) as I have made some changes for more modern package versions.

If there are any downstream uses, please contact me for proper attribution information.

## Installation
This contains the instructions for installation. 

First, ensure that you have Python 3.x installed.

Next, we create a virtual environment for the purposes of these tutorials so any installations do not interfere with any local packages. To do this, first:

    python3 -m venv bayes-tutorial
    source bayes-tutorial/bin/activate
    
This will create and activate your virtual environment.

Now, install the required packages:

    pip -r requirements-bayestutorial.txt

This may take a while, but at the end, we should be ready to procede.

All of the notebooks we will use should be run from within the virtual environment.
To activate:

    source bayes-tutorial/bin/activate

To deactivate:

    deactivate

## Contents
1. Intro
    - Intro-to-Bayes
