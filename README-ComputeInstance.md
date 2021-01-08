# Azure ML Workshop - Compute Instance

## Pre-requisites 

### Provision Azure ML Workspace within a new Azure Resource Group

- Login to https://portal.azure.com (Assuming you have an Azure Subscription that you can use for the labs).

- Provision Azure Machine Learning Workspace (Please follow instructions on below link and refer suggestions below to help you choose right configuration options).

  https://docs.microsoft.com/en-us/azure/machine-learning/how-to-manage-workspace?tabs=azure-portal#create-a-workspace
  
  - On 'Basics' tab, please click 'Create new' link below the 'Resource group' drop-down list and enter the name of new Resource Group whithin which the new workspace will be provisioned.
  
  - On 'Basics' tabs, please enter name of workspace e.g. aml-labs-workspace
  
  - On 'Networking' tab, please select 'Public endpoint (all networks)' as this is a labs environment.
  
  - Please keep the default options selected for remaining settings and click 'Create' on 'Review & Create' tab.

### Download this repository
This is required to have the datasets locally available for the labs.

Code -> Download as zip

### Provisioning the Compute for the labs
- Please refer to Lab-00. Ideally resources should be created not more than a day before the workshop.

### Clean-up (Post workshop)
Please delete the resource group including all resources within it after finishing the workshop/labs.
