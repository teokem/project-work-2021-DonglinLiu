[![DOI](https://zenodo.org/badge/351414777.svg)](https://zenodo.org/badge/latestdoi/351414777)
# Abstract
This project an introduction tutorial for showing how conditional variational autoencoder(CVAE) works and how to use it for anamoly detection.  
There's no need to train the model if you don't want, the result data has been saved in .csv files.  
* [vae_z.csv](https://github.com/teokem/project-work-2021-DonglinLiu/blob/main/data/vae_z.csv) is test dataset in latent space acquired by VAE model.  
* [cvae_z.csv](https://github.com/teokem/project-work-2021-DonglinLiu/blob/main/data/cvae_z.csv) is test dataset in latent space acquired by CVAE model.

# Instructions for running the notebook
1. install [miniconda3](https://docs.conda.io/en/latest/miniconda.html).
2. In the terminal, navigate to the folder you downloaded from GitHub
3. Creating a new conda virtual environment for project.   
  ```conda env create -f environment.yml```   
5. Actiating the virtual environment and run jupyter lab.   
  ```source activate tf_2```   
  ```conda activate jupyter-lab```   
  
# Environment Packages
* python=3.6 is required to interprate the python code in this notebook
* jupyterlab=3.0.12 is required to run the notebook
* numpy=1.19.2 is used for the numpy array data structure
* pandas=1.2 is used for building data structure
* scikit-learn=0.24.1 is used for clustering
* matplotlib=3.3 is used for plotting
* tensorflow=2.4.1 is used for building the model
