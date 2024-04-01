This repository contains code used in manuscript titled "Lunar Crustal KREEP Distribution" submitted to JGR planets by Janette Levin in March, 2024.

All code is written by Janette Levin (janette_levin@brown.edu) unless otherwise specified.
#########################################################################################

# Directory Description

> environment.yml : Python environment file containing python dependencies

> data/ : directory containing script to download necessary data

> results/ : directory containing data products 
> notebooks/ : directory containing jupyter notebooks
> src/ : directory containing .py files
 
#####################################################################################

Code for Figures available in 

notebooks/

################
# Instructions: 

## Set up conda environment:

To set up conda environment from provided  environment.yml file in a directory, navigate to directory in Terminal and run the following command:

> conda env create --prefix ./envs -f environment.yml

(For detailed instructions, see https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#creating-an-environment-from-an-environment-yml-file ) 

## Activate conda environment 

> conda activate ./envs

## Open Jupyter Lab: 

> jupyter lab

You will now be able to navigate to notebooks/ within Jupyter Lab and run notebooks

## Download data: 

Navigate to data/
 