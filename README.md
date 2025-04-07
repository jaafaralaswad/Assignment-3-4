![Python Version](https://img.shields.io/badge/python-3.12-blue)
![OS](https://img.shields.io/badge/os-ubuntu%20%7C%20macos%20%7C%20windows-blue)
![License](https://img.shields.io/badge/license-MIT-green)


# ME700 Assignment 3 Part 4

## Table of Contents

- [Introduction](#introduction)
- [Conda Environment, Installation, and Testing](#conda-environment-installation-and-testing)
- [More Information](#more-information)

## Introduction
This repository presents the work developed to fulfill the requirements of Assignment 3 Part 4 for the course ME700.


## Conda environment, install, and testing

This procedure is very similar to what we did in class. First, you need to download the repository and unzip it. Then, to install the package, use:

```bash
conda create --name assignment-3-4-env python=3.12
```

After creating the environment (it might have already been created by you earlier), make sure to activate it, use:

```bash
conda activate assignment-3-4-env
```

Check that you have Python 3.12 in the environment. To do so, use:

```bash
python --version
```

Create an editable install of the assignemnt codes. Use the following line making sure you are in the correct directory:

```bash
pip install -e .
```

You must do this in the correct directory; in order to make sure, replace the dot at the end by the directory of the folder "Assignment-3-4-main" that you unzipped earlier: For example, on my computer, the line would appear as follows:

```bash
pip install -e /Users/jaafaralaswad/Downloads/Assignment-3-4-main
```

To run the tutorials, make sure you are in the tutorials directory. You can navigate their as you navigated to the tests folder. On my computer, I would use:

```bash
cd /Users/jaafaralaswad/Downloads/Assignment-3-4-main/tutorials
```

Once you are there, you can use:

```bash
pip install jupyter
```

Depending on which tutorial you want to use, you should run one of the following lines:


```bash
jupyter notebook tutorial 1.ipynb
```

```bash
jupyter notebook tutorial 2.ipynb
```

```bash
jupyter notebook tutorial 3.ipynb
```

A Jupyter notebook will pop up.



## More information

To be written
