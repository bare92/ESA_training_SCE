# ESA Training SCE

This repository contains the necessary files and instructions to set up an environment for ESA training using the `esa_training_env.yml` file. Follow the steps below to get started.

## Cloning the Repository

To clone this repository, open your terminal and run the following command:

```bash
git clone https://github.com/bare92/ESA_training_SCE.git

cd ESA_training_SCE/

conda env create -f esa_training_env.yml

conda activate esa

jupyter notebook
