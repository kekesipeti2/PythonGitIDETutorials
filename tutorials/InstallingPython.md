# Installing Python Guide

This page details the necessary steps to install **Python** on your machine.

Python has a rich **package** library, therefore it is recommended to create seperate environments for your packages. Each **environment** acts as a seperate workspace, there is no content sharing between your environments. 

The recommended environment and package handling software for Python is [Anaconda](https://www.anaconda.com/products/individual).
After installing Anaconda you can open Anaconda Navigator and create a new environment. 

 1. Head to `Environments` menu.
 2. Click on `Create`.
 3. Enter an Environment name and click on `Create`. Make sure to select a Python version above 3.0, because there is no backwards compatibility to Python 2.

![Anaconda environments](/tutorials/imgs/img1.jpg)

Now your environment has been created and you can install packages from the Anaconda command line. Open Anaconda prompt and type the following command to switch to your environment:

    conda activate <your-env-name>
    # Example: conda activate python-env
You can check your installed packages with:

    conda list
To install new packages use either pip or conda. Using both package installers at the same time is not recommended. From my experience **pip** is better and easier to use. To install a package use the command:

    pip install <your-package>
    # Example: pip install numpy
