## ABE-4662 Quantification of Biological Processes
______________________________________
Working to put ABE 4662 on Github version 5.20.21

## Topics covered:


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
