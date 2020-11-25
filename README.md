# AzureMLWorkshop
Azure ML Workshop Labs

## Install new Conda Environment and Install Azure ML SDK

conda create --name amllabs python==3.8.3

conda update -n base -c defaults conda

conda activate amllabs

pip install azureml-sdk

conda install notebook ipykernel

ipython kernel install --user --name amllabs --display-name "Python 3.8.3 (amllabs)"
