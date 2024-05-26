## Reproducibility ##
Due to the use of mutually incompatible libraries for different parts of the project, two different environments had to be used. In order to run the `EDA.ipynb` and `NN.ipynb` notebooks, the following commands have to be run from within this folder:

`
conda env create -f environment_eda.yml
`

In order to activate the environment, run the following command:

`
conda activate Project_EDA
`

In order to run `LTN.ipynb`, use the following commands:

`
conda env create -f environment_ltn.yml
`

environment can be activated by running:

`
conda activate Project_LTN
`

Code related to work, that did not end up in the final report, can be found in the development branch of the repository.