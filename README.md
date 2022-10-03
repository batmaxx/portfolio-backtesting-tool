# portfolio-backtesting-tool
This repository contains the notebook and data used in the Medium post: <link to medium post>
## How to set up a conda environment
### Install Anaconda
If you don't already have anaconda or miniconda installed, download and install one of the two:   

- To chose between Anaconda or Miniconda: https://docs.conda.io/projects/conda/en/latest/user-guide/install/download.html#anaconda-or-miniconda
- Anaconda documentation: https://www.anaconda.com/products/distribution
- Miniconda documentation: https://docs.conda.io/en/latest/miniconda.html

Once installed, open a new **Anaconda Prompt**


### Clone repository
`git clone https://github.com/batmaxx/portfolio-backtesting-tool`


### Create a new conda environment
`conda create -n portfolio-backtesting-tool-env python=3.9`


### Activate the environment
`conda activate portfolio-backtesting-tool-env`


### Install dependencies
In the root folder of the project (*.../portfolio-backtesting-tool*)

`pip install -r requirements.txt`


### Launch jupyter lab
`jupyter lab`

You should be good to go, you can now open the `Notebook.ipynb` in your browser and start hacking!