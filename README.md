## ABE-4662
______________________________________
Working to put ABE 4662 on Github

## Topics covered:

1. [Basic Python](00-Studying-Mathematics-with-Python.ipynb)
2. [Using Sympy](01-Symbolic-mathematics-with-Sympy.ipynb) for symbolic
   mathematics.
3. [Using Numpy](02-Linear-algebra-with-Numpy.ipynb) for linear algebra.
4. [Using Pandas](03-Data-analysis-with-Pandas.ipynb) for basic handling of
   data.
5. [Using matplotlib for visualisation](04-Visualisation-with-matplotlib.ipynb)
   for visualisation.

## Creating the pdfs and tex files:

Create the conda environment from the file:

    $ conda env create -f environment.yml

Source the conda environment:

    $ conda source pfm

Run the following command:

    $ inv main

## Testing the notebooks

It is possible to test that the notebooks run:

    $ inv test
