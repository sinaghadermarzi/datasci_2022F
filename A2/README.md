# Detailed versions

The detailed versions of python, numpy and pandas used in testing your assignment are:

  - python 3.10.4
  - numpy 1.23.1
  - pandas 1.4.3

# Reproducing the testing environment using conda

You can use **conda** to reproduce the same environment in your system. (Find instructions for installing conda [here](https://docs.conda.io/projects/conda/en/latest/user-guide/install/))

Once you have conda installed, 

1. Download the `environment.yml` file in this folder of the repository and copy/move it to your working folder 

2. Create the environment by entering the following command in the command line (I assume you have Linux or Mac but on windows everything should be pretty similar) 

```bash
conda env create -p cenv/ -f environment.yml

```

3. activate the environment by entering the following command:

```bash
conda activate cenv/
```

4. Then you will see the path to your environment in a parenthesis before your command prompt (something like `(/home/../cenv)` ). Which means the environment is activated. Now you can be sure that you are using the same version as the testing environment.  

