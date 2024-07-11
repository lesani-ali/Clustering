
# Clustering Algorithms from Scratch

## Overview

This repository aims to provide a collection of clustering algorithms implemented from scratch using Python. Currently, it features an implementation of the KMeans algorithm, tested on the MNIST dataset and compared with the sklearn KMeans implementation. More clustering algorithms will be added in the future.


## Project Structure
```
Clustering/
├── classes/                   # Directory containing class implementations
│   ├── __init__.py
│   ├── KMeans.py              # KMeans implementation
├── main.ipynb                 # Notebook demonstrating the use of clustering algorithms
├── .gitignore                 # Git ignore file
├── environment.yml            # Python dependencies
└── README.md                  # Project README file
```


## Cloning Repository from GitHub
Use this command to clone the repository from GitHub: <br>
`git clone git@github.com:lesani-ali/Clustering.git`<br> 


## Environment Setup
Please follow these steps to set up the working environment:
1. Install Miniconda (use terminal to execute these commands):
    - Create a Directory:<br>
    `mkdir -p ~/miniconda3`
    - Download the Miniconda Installer:<br>
    `curl https://repo.anaconda.com/miniconda/Miniconda3-latest-MacOSX-arm64.sh -o ~/miniconda3/miniconda.sh`
    - Run the Miniconda Installer:<br>
    `bash ~/miniconda3/miniconda.sh -b -u -p ~/miniconda3`
    - Remove the Installer Script:<br>
    `rm -rf ~/miniconda3/miniconda.sh`
    - Add to path:<br>
    `source ~/miniconda3/bin/activate`
    - Initialize for bash and zsh shells:<br>
    `~/miniconda3/bin/conda init bash`<br>
    and <br>
    `~/miniconda3/bin/conda init zsh`

    For more information visit [Miniconda](https://docs.anaconda.com/miniconda/) website.

2. Create conda environment and install all packages (I used "data_collection" as a name for my environment): <br>
`conda env create -f environment.yml`

3. Activate the environment: <br>
`conda activate ML`

## Acknowledgements
- The MNIST dataset is provided by Yann LeCun and can be found [here](http://yann.lecun.com/exdb/mnist/).