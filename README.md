# ESA Training SCE

This repository contains the necessary files and instructions to set up an environment for ESA training using the `esa_training_env.yml` file. Follow the steps below to get started.

## Cloning the Repository

To clone this repository, open your terminal and run the following command:

For Ubuntu os:
```bash
git clone https://github.com/bare92/ESA_training_SCE.git

cd ESA_training_SCE/

conda env create -f esa_training_env.yml

conda activate esa

jupyter notebook
```

For Windows os:

```bash
git clone https://github.com/bare92/ESA_training_SCE.git

cd ESA_training_SCE/

conda env create -f esa_training_env_win.yml

conda activate esa

jupyter notebook
```



As alternative in case previous solutions are not working:
```bash

conda create --name esa -c conda-forge python=3.9 spyder gdal jupyter scipy rasterio pandas geopandas shapely fiona opencv pyproj

conda install anaconda::scikit-learn

conda install anaconda::scikit-image

conda activate esa

jupyter notebook
```
