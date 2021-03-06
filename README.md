## ABE-4662 Quantification of Biological Processes
______________________________________
Working to put ABE 4662 on Github version 5.20.21,
This Course was designed to integrate into content provided by J. Kantor from Univ. Notre Dame, a special thanks to him for allowing access to his excellent work!

## Topics covered:


Here are sets of Jupyter/Python notebooks in support of **ABE 4662 Quantification of Biological Process**,
Please note there is a companion site
on CANVAS with additional notebooks, videos, course assignments and a bunch of other stuff.

The links below display the notebooks as regular HTML web pages. From there you can run the notebook on
[Google Colaboratory](https://colab.research.google.com) or download to run on your own laptop. To run on your own
laptop you will need to install Jupyter and Python 3, such as the excellent
[Anaconda distribution from Continuum Analytics](https://www.continuum.io/downloads).


### [Table of Contents](http://nbviewer.jupyter.org/github/jckantor/CBE30338/blob/master/notebooks/toc.ipynb?flush=true)

### [Chapter 1.0 Getting Started](http://nbviewer.jupyter.org/github/jckantor/CBE30338/blob/master/notebooks/01.00-Getting-Started.ipynb)
- [1.1 Getting Started with Python and Jupyter Notebooks](http://nbviewer.jupyter.org/github/jckantor/CBE30338/blob/master/notebooks/01.01-Getting-Started-with-Python-and-Jupyter-Notebooks.ipynb)
- [1.2 Python Basics](http://nbviewer.jupyter.org/github/jckantor/CBE30338/blob/master/notebooks/01.02-Python-Basics.ipynb)
- [1.3 Python Conditionals and Libraries](http://nbviewer.jupyter.org/github/jckantor/CBE30338/blob/master/notebooks/01.03-Python-Conditionals-and-Libraries.ipynb)
- [1.4 Python Numeric Integration Revisited](http://nbviewer.jupyter.org/github/jckantor/CBE30338/blob/master/notebooks/01.04-Python-Numeric-Integration-Revisited.ipynb)

### Chapter 2.0 Class Tutorials to Python
- [2.1  Tutorial 0 Python and Jupyter Notebooks](https://nbviewer.jupyter.org/github/correllmj/ABE-4662/blob/master/PythonTutorialZero.ipynb)
- [2.2 Tutorial 1 Python](https://nbviewer.jupyter.org/github/correllmj/ABE-4662/blob/master/Python%20Tutorial%20%201%20Jupyter%20Notebook%20Version%20(1).ipynb)
- [2.3 Python Conditionals and Libraries](http://nbviewer.jupyter.org/github/jckantor/CBE30338/blob/master/notebooks/01.03-Python-Conditionals-and-Libraries.ipynb)
- [2.4 Python Numeric Integration Revisited](http://nbviewer.jupyter.org/github/jckantor/CBE30338/blob/master/notebooks/01.04-Python-Numeric-Integration-Revisited.ipynb)

## Creating the pdfs and tex files:
testing
Create the conda environment from the file:

    $ conda env create -f environment.yml

Source the conda environment:

    $ conda source pfm

Run the following command:

    $ inv main

## Testing the notebooks

It is possible to test that the notebooks run:

    $ inv test
