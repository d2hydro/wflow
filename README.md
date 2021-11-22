# wflow
wflow model builder

## download and install wflow
wflow is a Deltares product. The documentation can be found [here](https://deltares.github.io/Wflow.jl/stable).
And a shortcut to the download page can be found here [here](https://download.deltares.nl/en/download/wflow).
In our approoach we run wflow from the Command-Line Interface (CLI). These instructions are found [here](https://deltares.github.io/Wflow.jl/stable/cli/#Command-Line-Interface).

## prepare your Python environment
Make sure you have an Miniconda or Anaconda installation. You can download these here:
 - https://www.anaconda.com/products/individual
 - https://docs.conda.io/en/latest/miniconda.html


Use the [environment.yml](./env/environment.yml) in this repository to create the wflow environment we use to build models via de command-line:

```
conda env create -f environment.yml
```

After installation you can activate your environment in command prompt:

```
conda activate wflow
```

## create a wflow model using the HYDROBASE API
Navigate to the ./notebooks folder in this repository. Start Jupyter Notebook in the command-line by:
```
Jupyter Notebook
```

Open the Jupyter Notebook" [wflow-model from hydrobase](./notebooks/wflow-model_from_hydrobase.ipynb) and follow the instructions. 

## execute your wflow model using the command-line interface
Now you have created your wflow-model, you can run it in the command-line interface as explained in the [wflow instructions](https://deltares.github.io/Wflow.jl/stable/cli/#Command-Line-Interface)