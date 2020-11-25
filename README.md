# AzureMLWorkshop
Azure ML Workshop Labs created as Jupyter Notebooks.

- The batch files are built on Windows platform.

- Please change the path in Launch Jupyter Notebook Batch.bat to directory where you have cloned this repo.

## Pre-requisite 

Install Jupyter Notebook (if not already done)

https://www.anaconda.com/products/individual

## Install new Conda Environment and Install Azure ML SDK

conda create --name amllabs python==3.8.3

conda update -n base -c defaults conda

conda activate amllabs

pip install azureml-sdk

conda install notebook ipykernel

ipython kernel install --user --name amllabs --display-name "Python 3.8.3 (amllabs)"

## Cloning the repo
git clone "https://github.com/MaheshSQL/AzureMLWorkshop.git"

## Launch Jupyter Notebook
cd "DIRECTORY PATH WHERE THE REPO IS CLONED"

conda activate amllabs

jupyter notebook
